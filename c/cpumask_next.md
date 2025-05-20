# Function: <code>cpumask_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007b4f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008410)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/core.c (ffffffff8100b13d)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100ebf3)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_cpu_notifier
  - arch/x86/events/intel/cqm.c:intel_cqm_cpu_notifier
```
```
In arch/x86/events/intel/cstate.c (ffffffff8100f151)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
```
```
In arch/x86/events/intel/ds.c (ffffffff810102b4)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81f5f9e2)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In arch/x86/events/intel/rapl.c (ffffffff81014f08)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_cpu_init
  - arch/x86/events/intel/rapl.c:rapl_pmu_init
  - arch/x86/events/intel/rapl.c:rapl_cpu_notifier
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015cb2)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_cpu_starting
  - arch/x86/events/intel/uncore.c:uncore_cpu_notifier
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In arch/x86/xen/enlighten.c (ffffffff8101c568)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
```
```
In arch/x86/xen/mmu.c (ffffffff81020791)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/time.c (ffffffff81023b56)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/suspend.c (ffffffff810241cc)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
```
```
In arch/x86/xen/smp.c (ffffffff8102b5db)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In arch/x86/kernel/irq.c (ffffffff81030121)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/irqinit.c (ffffffff81033897)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:vector_used_by_percpu_irq
```
```
In arch/x86/kernel/topology.c (ffffffff81f68ce2)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/tsc.c (ffffffff810384c1)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f4a7)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81041916)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_start
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044275)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81f6b11e)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81f6b187)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104c909)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81f6f66f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81f6fe7a)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81054b82)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105522b)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81059457)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059843)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059ca5)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/kernel/crash.c (ffffffff8105ddd3)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/kgdb.c (ffffffff81060fda)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
```
```
In arch/x86/kernel/hpet.c (ffffffff81f742c5)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810747ff)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff81f78624)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/fork.c (ffffffff8107e143)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/fork.c:nr_processes
```
```
In kernel/cpu.c (ffffffff81081bb3)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/softirq.c (ffffffff81f7b9f1)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
```
```
In kernel/workqueue.c (ffffffff8109b493)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/smpboot.c (ffffffff810a3aa2)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/smpboot.c:idle_threads_init
```
```
In kernel/sched/core.c (ffffffff810a5ec8)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/core.c:register_sched_domain_sysctl
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
```
```
In kernel/sched/clock.c (ffffffff810b1342)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init
```
```
In kernel/sched/fair.c (ffffffff810b2487)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:sched_group_set_shares
```
```
In kernel/sched/rt.c (ffffffff810bf25b)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff810c2b64)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (ffffffff810c431d)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810c48ee)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/stats.c (ffffffff810c540f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810c5a8f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
```
```
In kernel/sched/cpuacct.c (ffffffff810c96be)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:cpuusage_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810ca19c)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In kernel/locking/lglock.c (ffffffff810ca555)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/locking/lglock.c:lg_global_lock
  - kernel/locking/lglock.c:lg_global_unlock
```
```
In kernel/irq/irqdesc.c (ffffffff810da226)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:kstat_irqs
```
```
In kernel/irq/proc.c (ffffffff810e2328)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
```
In kernel/rcu/srcu.c (ffffffff810e3b4d)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:cleanup_srcu_struct
  - kernel/rcu/srcu.c:try_check_zero
```
```
In kernel/rcu/tree.c (ffffffff810e4b9b)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_init
```
```
In kernel/profile.c (ffffffff810ea1d1)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In kernel/time/timer.c (ffffffff810ee513)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_migration
  - kernel/time/timer.c:init_timers
```
```
In kernel/time/clocksource.c (ffffffff810f8479)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/timer_list.c (ffffffff810f9350)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
```
In kernel/time/clockevents.c (ffffffff81f808ff)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_init_sysfs
```
```
In kernel/time/tick-broadcast.c (ffffffff810fcf1c)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/time/tick-sched.c (ffffffff810feec3)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_clock_notify
```
```
In kernel/time/timer_stats.c (ffffffff810ff451)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/time/timer_stats.c:tstats_write
  - kernel/time/timer_stats.c:init_timer_stats
```
```
In kernel/smp.c (ffffffff81103cdf)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:call_function_init
  - kernel/smp.c:smp_init
```
```
In kernel/module.c (ffffffff811072f2)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/module.c:is_module_percpu_address
  - kernel/module.c:load_module
```
```
In kernel/stop_machine.c (ffffffff811200be)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
```
```
In kernel/debug/gdbstub.c (ffffffff81130afb)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113585e)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81139068)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff81139e08)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/relay.c (ffffffff8113c990)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/taskstats.c (ffffffff8113e4ff)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:taskstats_init_early
```
```
In kernel/trace/ftrace.c (ffffffff81f8360e)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_profile_write
```
```
In kernel/trace/ring_buffer.c (ffffffff81146a78)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:rb_cpu_notify
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff8114b019)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8115923e)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/trace/trace_events.c (ffffffff8115f15a)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff8116274f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_kdb.c (ffffffff8116ca86)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f536)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/core.c (ffffffff8117932e)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_event_init
```
```
In kernel/events/callchain.c (ffffffff8118601b)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/hw_breakpoint.c (ffffffff81186512)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
```
In kernel/padata.c (ffffffff811898ba)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/padata.c:padata_index_to_cpu
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/page_alloc.c (ffffffff8181cce7)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:zone_pcp_reset
```
```
In mm/swap.c (ffffffff8119e308)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
```
```
In mm/vmstat.c (ffffffff811ac6d2)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:vmstat_cpuup_callback
  - mm/vmstat.c:set_pgdat_percpu_threshold
```
```
In mm/percpu.c (ffffffff811b0765)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:is_kernel_percpu_address
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/vmalloc.c (ffffffff811cce54)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vm_unmap_aliases
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/swapfile.c (ffffffff811d6939)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/zswap.c (ffffffff811d7e69)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
```
```
In mm/slub.c (ffffffff811e7bd9)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
```
```
In mm/memory_hotplug.c (ffffffff811efa84)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/memcontrol.c (ffffffff811fa44f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff81f8db08)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_init
```
```
In mm/zsmalloc.c (ffffffff8120901e)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_unregister_cpu_notifier
```
```
In fs/dcache.c (ffffffff812254ed)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
```
```
In fs/inode.c (ffffffff81226a44)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - fs/inode.c:get_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:proc_nr_inodes
```
```
In fs/namespace.c (ffffffff8122cb43)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - fs/namespace.c:mnt_get_count
```
```
In fs/seq_file.c (ffffffff8123110b)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hlist_start_percpu
```
```
In fs/buffer.c (ffffffff812432ee)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In fs/locks.c (ffffffff81f906d3)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - fs/locks.c:filelock_init
```
```
In fs/proc/stat.c (ffffffff81282dbd)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In fs/proc/uptime.c (ffffffff812833e9)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In fs/proc/softirqs.c (ffffffff81283565)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
```
```
In fs/ext4/super.c (ffffffff812b8035)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/mballoc.c (ffffffff812d3521)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/sysfs.c (ffffffff812e3aed)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In security/apparmor/lsm.c (ffffffff8139be7a)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - security/apparmor/lsm.c:destroy_buffers
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-softirq.c (ffffffff81f9b315)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In block/blk-iopoll.c (ffffffff81f9b37f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - block/blk-iopoll.c:blk_iopoll_setup
```
```
In block/blk-mq.c (ffffffff813c37e6)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-sysfs.c (ffffffff813c8090)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
```
```
In block/blk-mq-cpumap.c (ffffffff813c8669)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In block/genhd.c (ffffffff813ca40f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff813ccc16)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:delete_partition_rcu_cb
```
```
In lib/cpumask.c (ffffffff813e91bc)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_next_and
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_any_but
```
```
In lib/nmi_backtrace.c (ffffffff813edc56)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
```
```
In lib/random32.c (ffffffff813f89d4)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed_full_state
```
```
In lib/percpu-refcount.c (ffffffff813ff046)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/percpu_ida.c (ffffffff813ff5d5)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_for_each_free
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/percpu_counter.c (ffffffff81411a7c)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_set
  - lib/percpu_counter.c:__percpu_counter_sum
```
```
In lib/iommu-common.c (ffffffff81413267)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_pool_init
```
```
In lib/cpu_rmap.c (ffffffff81415cc8)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/idle/intel_idle.c (ffffffff81479279)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_devices_uninit
```
```
In drivers/acpi/processor_core.c (ffffffff81482998)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff814ad2ce)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed
```
```
In drivers/acpi/processor_throttling.c (ffffffff814ad764)
Location: include/linux/cpumask.h:184
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_thermal.c (ffffffff814ae6ae)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
```
```
In drivers/acpi/processor_perflib.c (ffffffff814aebc4)
Location: include/linux/cpumask.h:184
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/dma/dmaengine.c (ffffffff814bcbc4)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
```
```
In drivers/xen/cpu_hotplug.c (ffffffff814c4556)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
```
```
In drivers/xen/events/events_base.c (ffffffff814c9a62)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
```
In drivers/xen/events/events_2l.c (ffffffff814c9fdf)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/events/events_fifo.c (ffffffff814cadac)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff816f452c)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
```
In drivers/base/topology.c (ffffffff81550e1e)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff815524c4)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:free_cache_attributes
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/base/node.c (ffffffff81560c80)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/net/loopback.c (ffffffff815e96f5)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/loopback.c:loopback_dev_init
```
```
In drivers/net/virtio_net.c (ffffffff815f1294)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_set_affinity
  - drivers/net/virtio_net.c:virtnet_probe
```
```
In drivers/net/xen-netfront.c (ffffffff815fa5e3)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
```
```
In drivers/md/md.c (ffffffff816f5699)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
```
```
In drivers/md/dm-stats.c (ffffffff816ac6c9)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816aebda)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff820b0dc4)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_exit
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b3bd1)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff816b4ee1)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff816b528d)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_check_cpu
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b5d34)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msrs
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b7501)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff816b984c)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816ba1f3)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:pid_param_set
```
```
In drivers/cpuidle/cpuidle.c (ffffffff816bbd0d)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81fb4ce7)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_exit
```
```
In arch/x86/pci/amd_bus.c (ffffffff81fbabc9)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
```
In net/socket.c (ffffffff81700269)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/socket.c:socket_seq_show
```
```
In net/core/sock.c (ffffffff817011c7)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/core/sock.c:sock_prot_inuse_get
```
```
In net/core/gen_stats.c (ffffffff8170eead)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic_cpu
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
```
In net/core/sysctl_net_core.c (ffffffff81713327)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff817158a5)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:netif_reset_xps_queues_gt
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/core/dst.c (ffffffff81723e3a)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/core/dst.c:metadata_dst_alloc_percpu
```
```
In net/core/neighbour.c (ffffffff81726728)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In net/core/flow.c (ffffffff81734454)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_new_hashrnd
  - net/core/flow.c:flow_cache_fini
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff8173642f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
```
```
In net/sched/sch_api.c (ffffffff817451ec)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/act_api.c (ffffffff817476b5)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_create
```
```
In net/ipv4/route.c (ffffffff81753848)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/tcp.c (ffffffff817669d0)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv4/tcp_output.c (ffffffff81fbce11)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177b87d)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff8178de0d)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_init
```
```
In net/ipv4/af_inet.c (ffffffff81793b75)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/af_inet.c:ipv4_mib_init_net
```
```
In net/ipv4/fib_semantics.c (ffffffff8179c288)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff8179f77d)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4993)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
```
In net/ipv6/af_inet6.c (ffffffff817c37f8)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff817cab23)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d3a54)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_alloc
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_init
```
```
In net/ipv6/ip6_fib.c (ffffffff817d9e44)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff817e741d)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_init
```
```
In net/packet/af_packet.c (ffffffff81805088)
Location: include/linux/cpumask.h:184
Inline: True
```
**Symbols:**

```
ffffffff814ad764-ffffffff814ad780: cpumask_next (STB_LOCAL)
ffffffff814aebc4-ffffffff814aebe0: cpumask_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007d44)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008545)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/events/intel/core.c (ffffffff8100b20a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
```
In arch/x86/events/intel/cqm.c (ffffffff81f86e8a)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fda5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81f8794f)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In arch/x86/xen/enlighten.c (ffffffff81891c27)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
  - arch/x86/xen/enlighten.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff81020772)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/time.c (ffffffff81022df6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/suspend.c (ffffffff810236bc)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
```
In arch/x86/xen/smp.c (ffffffff8102a7ab)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In arch/x86/kernel/irq.c (ffffffff8102fe84)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
```
```
In arch/x86/kernel/irqinit.c (ffffffff81032a5e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:vector_used_by_percpu_irq
```
```
In arch/x86/kernel/topology.c (ffffffff81f90bf2)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/tsc.c (ffffffff81f90fc7)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f2b1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81041846)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_start
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81f93287)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81f93427)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81f93493)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104c989)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810525a7)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:smp_init_package_map
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81f9859d)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81054ea3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055e36)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81059592)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059abd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a333)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/crash.c (ffffffff8105dc5c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/kgdb.c (ffffffff810616dd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107600f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff81fa0dd1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/fork.c (ffffffff8107fd9a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/fork.c:nr_processes
```
```
In kernel/cpu.c (ffffffff810841ae)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
```
```
In kernel/softirq.c (ffffffff81fa4788)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
```
```
In kernel/workqueue.c (ffffffff81fa5165)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810a73cd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/smpboot.c:idle_threads_init
```
```
In kernel/sched/core.c (ffffffff810ad689)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/clock.c (ffffffff810b3eb9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init
```
```
In kernel/sched/fair.c (ffffffff810c25ea)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/rt.c (ffffffff81fa73a0)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff81fa73f3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
```
```
In kernel/sched/cpupri.c (ffffffff810c7fdf)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810c8582)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/stats.c (ffffffff810c90af)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810c99cf)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpuacct.c (ffffffff810cdd01)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810ceb14)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In kernel/locking/lglock.c (ffffffff810cef44)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/locking/lglock.c:lg_global_unlock
  - kernel/locking/lglock.c:lg_global_lock
```
```
In kernel/printk/nmi.c (ffffffff81fa7ed6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/printk/nmi.c:printk_nmi_init
  - kernel/printk/nmi.c:printk_nmi_flush
```
```
In kernel/irq/irqdesc.c (ffffffff810dfad3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/proc.c (ffffffff810e7d8e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
```
In kernel/irq/affinity.c (ffffffff810e8e83)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_mask
```
```
In kernel/rcu/srcu.c (ffffffff810e9f8c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:try_check_zero
  - kernel/rcu/srcu.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff81fa8926)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/profile.c (ffffffff810f0f18)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/timer.c (ffffffff81fa8fcc)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/timer.c:init_timers
  - kernel/time/timer.c:timers_update_migration
```
```
In kernel/time/clocksource.c (ffffffff810ff6f0)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/timer_list.c (ffffffff811005d0)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
```
In kernel/time/clockevents.c (ffffffff81fa996b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_init_sysfs
```
```
In kernel/time/tick-broadcast.c (ffffffff81104c08)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff8110624a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_clock_notify
```
```
In kernel/time/timer_stats.c (ffffffff81fa9af5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/timer_stats.c:init_timer_stats
  - kernel/time/timer_stats.c:tstats_write
```
```
In kernel/smp.c (ffffffff8110b281)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
```
```
In kernel/module.c (ffffffff811108e8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:is_module_percpu_address
```
```
In kernel/stop_machine.c (ffffffff8112803f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
```
```
In kernel/debug/gdbstub.c (ffffffff81139dbf)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113dd0b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8114153f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff811422ac)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/relay.c (ffffffff81145817)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
```
```
In kernel/taskstats.c (ffffffff81fac7d9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ftrace.c (ffffffff8114e543)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_profile_write
```
```
In kernel/trace/ring_buffer.c (ffffffff81150a0b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_cpu_notify
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81fad1fd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81163ac8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/trace/trace_events.c (ffffffff81169a3e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff8116cf12)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_kprobe.c (ffffffff81174fc9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:probes_profile_seq_show
```
```
In kernel/trace/trace_kdb.c (ffffffff81179f19)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117ce16)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/hashtab.c (ffffffff811874ad)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff81187d05)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81188071)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
```
```
In kernel/events/core.c (ffffffff81fafa79)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
```
In kernel/events/callchain.c (ffffffff81198410)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
```
```
In kernel/events/hw_breakpoint.c (ffffffff811989c9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/padata.c (ffffffff8119c5c4)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_index_to_cpu
```
```
In mm/page_alloc.c (ffffffff811aca14)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/swap.c (ffffffff811b3c31)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff811ba7fe)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:pgdat_reclaimable
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/vmstat.c (ffffffff81fb1f0c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:vmstat_cpuup_callback
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
```
```
In mm/percpu.c (ffffffff81fb25b9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/compaction.c (ffffffff811d1fa6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/vmalloc.c (ffffffff811ea11f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_aliases
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/swapfile.c (ffffffff811f4a1e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/zswap.c (ffffffff81fb5447)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_pool_create
```
```
In mm/slub.c (ffffffff81206e20)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
```
```
In mm/memory_hotplug.c (ffffffff8120eed8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/memcontrol.c (ffffffff81fb7cbc)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In mm/memory-failure.c (ffffffff81fb8023)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_init
```
```
In mm/zsmalloc.c (ffffffff8122ecfc)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_unregister_cpu_notifier
```
```
In fs/dcache.c (ffffffff8124d5e5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
```
```
In fs/inode.c (ffffffff81251271)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
```
```
In fs/namespace.c (ffffffff81255606)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/namespace.c:mnt_get_count
```
```
In fs/seq_file.c (ffffffff81259412)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hlist_start_percpu
```
```
In fs/buffer.c (ffffffff8126b3c5)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In fs/locks.c (ffffffff81fbad44)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/locks.c:filelock_init
```
```
In fs/proc/stat.c (ffffffff812afe2f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In fs/proc/uptime.c (ffffffff812b0440)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In fs/proc/softirqs.c (ffffffff812b059f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
```
```
In fs/ext4/super.c (ffffffff812e6cf8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/mballoc.c (ffffffff81302c35)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/sysfs.c (ffffffff81313b2f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff8132572b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
```
```
In security/apparmor/lsm.c (ffffffff81fc42a9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
  - security/apparmor/lsm.c:destroy_buffers
```
```
In block/blk-softirq.c (ffffffff81fc6721)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In block/blk-mq.c (ffffffff81409355)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In block/blk-mq-sysfs.c (ffffffff8140c4b2)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
```
```
In block/blk-mq-cpumap.c (ffffffff8140ca69)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
```
```
In block/genhd.c (ffffffff8140e631)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff81411523)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_rcu_cb
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In lib/cpumask.c (ffffffff8142f49e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_any_but
  - lib/cpumask.c:cpumask_next_and
```
```
In lib/random32.c (ffffffff8143f90f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
```
```
In lib/percpu-refcount.c (ffffffff81446732)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/percpu_ida.c (ffffffff81446d43)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_for_each_free
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/percpu_counter.c (ffffffff8145983e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
```
```
In lib/iommu-common.c (ffffffff8145af7f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_pool_init
```
```
In lib/cpu_rmap.c (ffffffff8145dbfb)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/irq_poll.c (ffffffff81fca379)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/pci/msi.c (ffffffff814a0f61)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81fcbc40)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In drivers/acpi/processor_core.c (ffffffff814d149a)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff814fcca8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/acpi/processor_throttling.c (ffffffff814fd334)
Location: include/linux/cpumask.h:188
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_thermal.c (ffffffff814fe077)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
```
```
In drivers/acpi/processor_perflib.c (ffffffff814fec93)
Location: include/linux/cpumask.h:188
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/dma/dmaengine.c (ffffffff8150c653)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81514dc5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
```
```
In drivers/xen/events/events_base.c (ffffffff8151a593)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
```
In drivers/xen/events/events_2l.c (ffffffff8151ab46)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/events/events_fifo.c (ffffffff8151b92a)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff820e7791)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
```
```
In drivers/iommu/iova.c (ffffffff81580ab8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff81fd4e0c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:queue_flush_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff81fd7c6f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_exit
```
```
In drivers/base/topology.c (ffffffff815a2bf1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff81fd98e6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:free_cache_attributes
```
```
In drivers/base/node.c (ffffffff815b53bc)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/net/loopback.c (ffffffff81647eb2)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
```
```
In drivers/net/tun.c (ffffffff8164f9a0)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/net/virtio_net.c (ffffffff8165431b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_stats
```
```
In drivers/net/xen-netfront.c (ffffffff8165a4a8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
```
```
In drivers/md/md.c (ffffffff8175a31c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
```
```
In drivers/md/dm-stats.c (ffffffff8170e249)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81713d54)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81715bef)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81716fc7)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8175aa24)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msrs
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81719245)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff8171b215)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c47b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:pid_param_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8171d682)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81fe210a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff81fe86f5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
```
In net/socket.c (ffffffff81766d60)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/socket.c:socket_seq_show
```
```
In net/core/sock.c (ffffffff81767d3e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/sock.c:sock_prot_inuse_get
```
```
In net/core/gen_stats.c (ffffffff81776a7d)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/sysctl_net_core.c (ffffffff8177af8f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff8177d8b6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues_gt
```
```
In net/core/dst.c (ffffffff8178d891)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/dst.c:metadata_dst_alloc_percpu
```
```
In net/core/neighbour.c (ffffffff81790197)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/core/flow.c (ffffffff817a0590)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_fini
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_new_hashrnd
```
```
In net/core/net-sysfs.c (ffffffff817a25d7)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
```
```
In net/core/dst_cache.c (ffffffff817aadb3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_destroy
```
```
In net/sched/sch_api.c (ffffffff817b20b8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/act_api.c (ffffffff817b4a42)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_create
```
```
In net/ipv4/route.c (ffffffff81fea68c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/tcp.c (ffffffff817d47ae)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv4/tcp_output.c (ffffffff81feac74)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e90eb)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff817fb50a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/af_inet.c (ffffffff81801c04)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
```
```
In net/ipv4/fib_semantics.c (ffffffff81809e09)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff8180d336)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8181265e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
```
In net/ipv6/af_inet6.c (ffffffff818308a5)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81837b13)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fec0a4)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_dst_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff8184825d)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8185580b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_init
```
```
In net/packet/af_packet.c (ffffffff81875a7e)
Location: include/linux/cpumask.h:188
Inline: True
```
**Symbols:**

```
ffffffff814fd334-ffffffff814fd351: cpumask_next.constprop.8 (STB_LOCAL)
ffffffff814fec93-ffffffff814fecb0: cpumask_next.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007d5b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100856b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/events/intel/core.c (ffffffff8100b2ce)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
```
In arch/x86/events/intel/cqm.c (ffffffff81fc22f9)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ff15)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81fc2dc7)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In arch/x86/xen/enlighten.c (ffffffff818c653e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
  - arch/x86/xen/enlighten.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff81020e05)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/time.c (ffffffff81023546)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/suspend.c (ffffffff81023dec)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
```
In arch/x86/xen/smp.c (ffffffff81fc7f66)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
```
```
In arch/x86/kernel/irq.c (ffffffff8102fe21)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
```
```
In arch/x86/kernel/irqinit.c (ffffffff810326d5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:vector_used_by_percpu_irq
```
```
In arch/x86/kernel/topology.c (ffffffff81fcbf97)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/tsc.c (ffffffff81fcc385)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ecbd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81041296)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_start
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81044707)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045e0c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81fcea81)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ee80)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054ea7)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81fd3a64)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81057c6a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058be7)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c329)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c874)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d105)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/crash.c (ffffffff81060cea)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/kgdb.c (ffffffff81064794)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
```
```
In arch/x86/kernel/itmt.c (ffffffff810699c5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81079bc3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff81fdc56e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/fork.c (ffffffff81084591)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/fork.c:nr_processes
```
```
In kernel/cpu.c (ffffffff8108951f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/softirq.c (ffffffff81fe014b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
```
```
In kernel/workqueue.c (ffffffff810a6116)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/smpboot.c (ffffffff810acf09)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/smpboot.c:idle_threads_init
```
```
In kernel/sched/core.c (ffffffff810b3789)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/clock.c (ffffffff810ba4f9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init
```
```
In kernel/sched/fair.c (ffffffff810c866a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/rt.c (ffffffff81fe3044)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff81fe30b0)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
```
```
In kernel/sched/cpupri.c (ffffffff810cdfff)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810ce56a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/stats.c (ffffffff810cf0c1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810cf9f1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpuacct.c (ffffffff810d3d11)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d44c3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810d5780)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In kernel/printk/nmi.c (ffffffff81fe3c3c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/printk/nmi.c:printk_nmi_init
  - kernel/printk/nmi.c:printk_nmi_flush
```
```
In kernel/irq/irqdesc.c (ffffffff810e646a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
```
In kernel/irq/proc.c (ffffffff810ee7ce)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
```
In kernel/irq/affinity.c (ffffffff810efcdd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/srcu.c (ffffffff810f0e63)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:try_check_zero
  - kernel/rcu/srcu.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff810f24bd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/profile.c (ffffffff810f8008)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/timer.c (ffffffff81fe4e62)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/timer.c:init_timers
  - kernel/time/timer.c:timers_update_migration
```
```
In kernel/time/clocksource.c (ffffffff81102559)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/timer_list.c (ffffffff81103370)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
```
In kernel/time/clockevents.c (ffffffff81fe5920)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_init_sysfs
```
```
In kernel/time/tick-broadcast.c (ffffffff8110c352)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff8110d9ba)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_clock_notify
```
```
In kernel/time/timer_stats.c (ffffffff81fe5aaa)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/timer_stats.c:init_timer_stats
  - kernel/time/timer_stats.c:tstats_write
```
```
In kernel/smp.c (ffffffff811127f8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
```
```
In kernel/module.c (ffffffff81118106)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:is_module_percpu_address
```
```
In kernel/stop_machine.c (ffffffff81131cca)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
```
```
In kernel/debug/gdbstub.c (ffffffff81143b4f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81147ac2)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8114b31f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff8114c08c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/relay.c (ffffffff8114fc7b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
```
```
In kernel/taskstats.c (ffffffff81fe8af5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ftrace.c (ffffffff81158483)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_profile_write
```
```
In kernel/trace/ring_buffer.c (ffffffff8115d1aa)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81fe951d)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
```
```
In kernel/trace/trace_hwlat.c (ffffffff8116d7dc)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8116edf8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/trace/trace_events.c (ffffffff81174f05)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff811781d2)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_kprobe.c (ffffffff8118180b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:probes_profile_seq_show
```
```
In kernel/trace/trace_kdb.c (ffffffff81185a23)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_uprobe.c (ffffffff81188a26)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/hashtab.c (ffffffff81195455)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff81195cbc)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81196031)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81196eb4)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
```
In kernel/events/core.c (ffffffff81fec0f3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
```
In kernel/events/callchain.c (ffffffff811a7df0)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
```
```
In kernel/events/hw_breakpoint.c (ffffffff811a83b0)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/padata.c (ffffffff811ac30e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/page_alloc.c (ffffffff811bcfe4)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/swap.c (ffffffff811c42ba)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff811cae95)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:pgdat_reclaimable
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/vmstat.c (ffffffff81fee959)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
```
```
In mm/percpu.c (ffffffff81feef80)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/compaction.c (ffffffff811e1ed5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/vmalloc.c (ffffffff811fb485)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/swapfile.c (ffffffff812055be)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/slub.c (ffffffff81218e4e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
```
```
In mm/memory_hotplug.c (ffffffff81220fd9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/memcontrol.c (ffffffff81230247)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In mm/memory-failure.c (ffffffff81ff49e1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_init
```
```
In fs/dcache.c (ffffffff812606ac)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
```
```
In fs/inode.c (ffffffff81264378)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
```
```
In fs/namespace.c (ffffffff812689fd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/namespace.c:mnt_get_count
```
```
In fs/seq_file.c (ffffffff8126ca79)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hlist_start_percpu
```
```
In fs/buffer.c (ffffffff8127e50c)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In fs/locks.c (ffffffff81ff76ef)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/locks.c:filelock_init
```
```
In fs/proc/stat.c (ffffffff812c57ec)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In fs/proc/uptime.c (ffffffff812c5e37)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In fs/proc/softirqs.c (ffffffff812c5f8f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
```
```
In fs/ext4/super.c (ffffffff812fc8af)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/mballoc.c (ffffffff81318c6d)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/sysfs.c (ffffffff81329adb)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In security/apparmor/lsm.c (ffffffff813f08a8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - security/apparmor/lsm.c:destroy_buffers
```
```
In crypto/scompress.c (ffffffff813fa8c4)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
```
```
In block/blk-softirq.c (ffffffff82003131)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In block/blk-mq.c (ffffffff81423d44)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In block/blk-mq-sysfs.c (ffffffff814278b5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
```
```
In block/blk-mq-cpumap.c (ffffffff81427d39)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In block/genhd.c (ffffffff814299c1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff8142c8c3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_rcu_cb
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/blk-mq-pci.c (ffffffff81448b0b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
```
```
In lib/cpumask.c (ffffffff8144b6c2)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_any_but
  - lib/cpumask.c:cpumask_next_and
```
```
In lib/random32.c (ffffffff8145ca0f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
```
```
In lib/percpu-refcount.c (ffffffff814650e6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/percpu_ida.c (ffffffff81465533)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_for_each_free
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/percpu_counter.c (ffffffff814781fe)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
```
```
In lib/iommu-common.c (ffffffff81479a6f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_pool_init
```
```
In lib/cpu_rmap.c (ffffffff8147c6ec)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/irq_poll.c (ffffffff82007394)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In lib/sbitmap.c (ffffffff8148267e)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff82008c7b)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In drivers/acpi/processor_core.c (ffffffff814f35e5)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8151f924)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/acpi/processor_throttling.c (ffffffff815200c5)
Location: include/linux/cpumask.h:188
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_thermal.c (ffffffff81520d70)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
```
```
In drivers/acpi/processor_perflib.c (ffffffff81521892)
Location: include/linux/cpumask.h:188
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525305)
Location: include/linux/cpumask.h:188
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/dma/dmaengine.c (ffffffff81538761)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81541255)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
```
```
In drivers/xen/events/events_base.c (ffffffff81546a83)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
```
In drivers/xen/events/events_2l.c (ffffffff81547016)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/events/events_fifo.c (ffffffff81547df1)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff821cd645)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
```
```
In drivers/iommu/iova.c (ffffffff815ad468)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff82012837)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:queue_flush_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff820158cd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_exit
```
```
In drivers/base/cacheinfo.c (ffffffff815d2a82)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:free_cache_attributes
```
```
In drivers/base/node.c (ffffffff815e4693)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/net/loopback.c (ffffffff81678fc9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
```
```
In drivers/net/tun.c (ffffffff81681b5d)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/net/xen-netfront.c (ffffffff816881ff)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
```
```
In drivers/md/md.c (ffffffff81786815)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
```
```
In drivers/md/dm-stats.c (ffffffff8174079b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81745dbe)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81747910)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81748f34)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81786f44)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174b885)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff8174d008)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174ea32)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:pid_param_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81750272)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8201fee2)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In net/socket.c (ffffffff81793de7)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/socket.c:socket_seq_show
```
```
In net/core/sock.c (ffffffff81794d64)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/sock.c:sock_prot_inuse_get
```
```
In net/core/gen_stats.c (ffffffff817a3d03)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/sysctl_net_core.c (ffffffff817a85d3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff817aafad)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
```
```
In net/core/dst.c (ffffffff817bb161)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/dst.c:metadata_dst_alloc_percpu
```
```
In net/core/neighbour.c (ffffffff817bda4e)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/core/flow.c (ffffffff817cf180)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_fini
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_new_hashrnd
```
```
In net/core/net-sysfs.c (ffffffff817d0fc1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
```
```
In net/core/dst_cache.c (ffffffff817da3d3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_destroy
```
```
In net/sched/sch_api.c (ffffffff817e183a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/act_api.c (ffffffff817e4309)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_create
```
```
In net/ipv4/route.c (ffffffff82028f3d)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/tcp.c (ffffffff818044ee)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv4/tcp_output.c (ffffffff82029527)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818192e2)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff8182c3ba)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/af_inet.c (ffffffff81832b9b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
```
```
In net/ipv4/fib_semantics.c (ffffffff8183af8f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff8183e5c7)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843b5e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
```
In net/ipv4/proc.c (ffffffff81845840)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
```
```
In net/xfrm/xfrm_proc.c (ffffffff8185bd9d)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
```
In net/ipv6/af_inet6.c (ffffffff8186233c)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81869603)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/ipv6/route.c (ffffffff8202a9ab)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_dst_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff8187a0a8)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81887502)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_init
```
```
In net/ipv6/proc.c (ffffffff818a1049)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a48c1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
```
In net/packet/af_packet.c (ffffffff818a9f65)
Location: include/linux/cpumask.h:188
Inline: True
```
**Symbols:**

```
ffffffff815200c5-ffffffff815200e4: cpumask_next.constprop.5 (STB_LOCAL)
ffffffff81521892-ffffffff815218b1: cpumask_next.constprop.5 (STB_LOCAL)
ffffffff81525305-ffffffff81525324: cpumask_next.constprop.3 (STB_LOCAL)
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
In arch/x86/events/amd/core.c (ffffffff81007a91)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100821e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/events/intel/core.c (ffffffff8100b60f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e555)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff820a3041)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In arch/x86/xen/enlighten.c (ffffffff81019b68)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff8101b226)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/suspend.c (ffffffff8101b61c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff818fe1a0)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021f13)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/xen/smp.c (ffffffff81028e7b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
```
In arch/x86/xen/smp_pv.c (ffffffff820a85f7)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/smp_hvm.c (ffffffff820a886d)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
```
In arch/x86/kernel/irq.c (ffffffff8102e220)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
```
```
In arch/x86/kernel/irqinit.c (ffffffff81030914)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:vector_used_by_percpu_irq
```
```
In arch/x86/kernel/topology.c (ffffffff820ac6e2)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/tsc.c (ffffffff820acb26)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103cc84)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8103f3a6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_start
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810439ce)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045aec)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff820af439)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104edb2)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105480a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff820b474a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810573e9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058242)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105ba28)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bf83)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c574)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/crash.c (ffffffff8105fcee)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/kgdb.c (ffffffff810636c4)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
```
```
In arch/x86/kernel/itmt.c (ffffffff81068c35)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810784a7)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff820bd591)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/fork.c (ffffffff81081500)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/fork.c:nr_processes
```
```
In kernel/cpu.c (ffffffff81086644)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/softirq.c (ffffffff820c0f64)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
```
```
In kernel/workqueue.c (ffffffff810a30bb)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/smpboot.c (ffffffff810a9c44)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/smpboot.c:idle_threads_init
```
```
In kernel/sched/core.c (ffffffff810af701)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/clock.c (ffffffff810b4b53)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/sched/fair.c (ffffffff810c2344)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810c50bd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810c8c68)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
```
```
In kernel/sched/cpupri.c (ffffffff810ca946)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810cae69)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (ffffffff810cd6f6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/stats.c (ffffffff810ce2c0)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810cea60)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpuacct.c (ffffffff810d2eb1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d3633)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810d475b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
```
In kernel/printk/printk_safe.c (ffffffff820c4713)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
```
```
In kernel/irq/irqdesc.c (ffffffff810e5ac9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
```
In kernel/irq/proc.c (ffffffff810ee296)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
```
In kernel/irq/affinity.c (ffffffff810efcb8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/srcutree.c (ffffffff810f169e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff810f30eb)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/livepatch/transition.c (ffffffff810f9356)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/profile.c (ffffffff810fa048)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/timer.c (ffffffff820c5afd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/timer.c:init_timers
  - kernel/time/timer.c:timers_update_migration
```
```
In kernel/time/clocksource.c (ffffffff811046db)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/timer_list.c (ffffffff81105859)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
```
In kernel/time/clockevents.c (ffffffff820c6287)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_init_sysfs
```
```
In kernel/time/tick-broadcast.c (ffffffff8110d880)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff8110f8ba)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_clock_notify
```
```
In kernel/smp.c (ffffffff81113ce7)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
```
```
In kernel/module.c (ffffffff81119948)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__is_module_percpu_address
```
```
In kernel/stop_machine.c (ffffffff8113329a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
```
```
In kernel/debug/gdbstub.c (ffffffff8114593b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81149859)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8114d26f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff8114e03f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/relay.c (ffffffff81151f53)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
```
```
In kernel/taskstats.c (ffffffff820c9238)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ftrace.c (ffffffff8115b7cd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_write
```
```
In kernel/trace/ring_buffer.c (ffffffff811601be)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff820c9ef5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
```
```
In kernel/trace/trace_hwlat.c (ffffffff81170999)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81172018)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/trace/trace_events.c (ffffffff81177b54)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff8117aee2)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_kprobe.c (ffffffff811845db)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:probes_profile_seq_show
```
```
In kernel/trace/trace_kdb.c (ffffffff81188742)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b6ab)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/hashtab.c (ffffffff8119c6ff)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff8119d1f4)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8119d5c1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8119e23d)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
```
In kernel/events/core.c (ffffffff820cd0db)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
```
In kernel/events/callchain.c (ffffffff811af56b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
```
```
In kernel/events/hw_breakpoint.c (ffffffff811afb5f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/padata.c (ffffffff811b393e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/page_alloc.c (ffffffff811c5253)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
```
In mm/swap.c (ffffffff811cc6be)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In mm/vmscan.c (ffffffff811cfeef)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/vmstat.c (ffffffff820d09ec)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
```
```
In mm/percpu.c (ffffffff820d1338)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/compaction.c (ffffffff811ebcdc)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/swap_slots.c (ffffffff811ec6dc)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In mm/vmalloc.c (ffffffff812061c1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/swapfile.c (ffffffff81210dd3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/slub.c (ffffffff81224a02)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:__kmem_cache_create
```
```
In mm/memory_hotplug.c (ffffffff8122c8a3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/memcontrol.c (ffffffff8124047e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
```
```
In mm/memory-failure.c (ffffffff820d71ca)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_init
```
```
In fs/dcache.c (ffffffff8126de8b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
```
```
In fs/inode.c (ffffffff81271d27)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
```
```
In fs/namespace.c (ffffffff812761ac)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/namespace.c:mnt_get_count
```
```
In fs/seq_file.c (ffffffff8127a628)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hlist_start_percpu
```
```
In fs/buffer.c (ffffffff8128c1db)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In fs/locks.c (ffffffff820da730)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/locks.c:filelock_init
```
```
In fs/proc/stat.c (ffffffff812d2a0c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In fs/proc/uptime.c (ffffffff812d3048)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In fs/proc/softirqs.c (ffffffff812d318c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
```
```
In fs/ext4/mballoc.c (ffffffff8130fbb9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/super.c (ffffffff81331501)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/sysfs.c (ffffffff813396c6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In security/apparmor/lsm.c (ffffffff813ea501)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - security/apparmor/lsm.c:destroy_buffers
```
```
In crypto/scompress.c (ffffffff814071d5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
```
In block/blk-softirq.c (ffffffff820e69fb)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In block/blk-mq.c (ffffffff81432e06)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_next_cpu
```
```
In block/blk-stat.c (ffffffff81434326)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/blk-mq-sysfs.c (ffffffff81434d55)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
```
```
In block/blk-mq-cpumap.c (ffffffff81435129)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In block/genhd.c (ffffffff81437d11)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff81439bd3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_rcu_cb
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/blk-mq-pci.c (ffffffff81456f9b)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In block/blk-mq-virtio.c (ffffffff81457085)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
```
```
In lib/random32.c (ffffffff81461c21)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
```
```
In lib/percpu-refcount.c (ffffffff8146a0f6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/percpu_ida.c (ffffffff8146a8e3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_for_each_free
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/percpu_counter.c (ffffffff8148153e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
```
```
In lib/iommu-common.c (ffffffff81482dbe)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_pool_init
```
```
In lib/cpu_rmap.c (ffffffff81485a4d)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/irq_poll.c (ffffffff820e83cb)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In lib/sbitmap.c (ffffffff8148b9db)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
```
```
In drivers/idle/intel_idle.c (ffffffff820e9f9e)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In drivers/acpi/processor_core.c (ffffffff81501429)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81530eb8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/acpi/processor_throttling.c (ffffffff81531acd)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_thermal.c (ffffffff81532549)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
```
```
In drivers/acpi/processor_perflib.c (ffffffff815332bf)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81537f19)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/dma/dmaengine.c (ffffffff8154c070)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
```
```
In drivers/xen/cpu_hotplug.c (ffffffff815550e5)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
```
```
In drivers/xen/events/events_base.c (ffffffff8155a859)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
```
In drivers/xen/events/events_2l.c (ffffffff8155ade6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/events/events_fifo.c (ffffffff8155bd70)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff822c2802)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
```
```
In drivers/char/random.c (ffffffff815a8ad1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/char/random.c:invalidate_batched_entropy
```
```
In drivers/iommu/iova.c (ffffffff815c3078)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c6fa7)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:queue_flush_timeout
```
```
In drivers/iommu/intel-iommu.c (ffffffff820f757e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_exit
```
```
In drivers/base/cacheinfo.c (ffffffff815e75fe)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In drivers/base/node.c (ffffffff815f931f)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/net/loopback.c (ffffffff8168d958)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
```
```
In drivers/net/tun.c (ffffffff81696af6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816992e8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8169d59e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
```
```
In drivers/md/md.c (ffffffff81746db3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
```
```
In drivers/md/dm-stats.c (ffffffff8175a46d)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81764190)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81765fc9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817675d4)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81768d74)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8176a531)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff8176b686)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176c39e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:pid_param_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8176ed32)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8210296c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In net/socket.c (ffffffff817b21b6)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/socket.c:socket_seq_show
```
```
In net/core/sock.c (ffffffff817b2f51)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/sock.c:sock_prot_inuse_get
```
```
In net/core/gen_stats.c (ffffffff817c1da3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/sysctl_net_core.c (ffffffff817c6c1a)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff817c961c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
```
```
In net/core/dst.c (ffffffff817d9af8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/dst.c:metadata_dst_alloc_percpu
```
```
In net/core/neighbour.c (ffffffff817dc532)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/core/flow.c (ffffffff817ee510)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_fini
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_new_hashrnd
```
```
In net/core/net-sysfs.c (ffffffff817f018b)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
```
```
In net/core/dst_cache.c (ffffffff817f9643)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/core/gro_cells.c (ffffffff817f9a3a)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81800d99)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/act_api.c (ffffffff81803d46)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_create
```
```
In net/ipv4/route.c (ffffffff8210c4a9)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/tcp.c (ffffffff818247b3)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv4/tcp_output.c (ffffffff8210ca92)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81839a01)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff8184d751)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/af_inet.c (ffffffff81853ec8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
```
```
In net/ipv4/fib_semantics.c (ffffffff8185c451)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff8185fb0e)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818653ee)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
```
In net/ipv4/proc.c (ffffffff81867371)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
```
```
In net/xfrm/xfrm_proc.c (ffffffff81880479)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
```
In net/ipv6/af_inet6.c (ffffffff81886ac5)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8188d240)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
```
```
In net/ipv6/route.c (ffffffff8210e060)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_dst_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f83a)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff818adab1)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/proc.c (ffffffff818c76c8)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb12c)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
```
In net/packet/af_packet.c (ffffffff818d0afc)
Location: include/linux/cpumask.h:188
Inline: True
```
```
In lib/cpumask.c (ffffffff818ebd86)
Location: include/linux/cpumask.h:188
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/cpumask.c:cpumask_next_and
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81971d69)
Location: lib/cpumask.c:16
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/cpumask.c:cpumask_next_and
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_next
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:init_cpu_to_node
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/membarrier.c:SyS_membarrier
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/timer.c:timers_update_migration
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:load_module
  - kernel/module.c:__is_module_percpu_address
  - kernel/cgroup/stat.c:cgroup_stat_boot
  - kernel/cgroup/stat.c:cgroup_stat_exit
  - kernel/cgroup/stat.c:cgroup_stat_init
  - kernel/cgroup/stat.c:cgroup_stat_flush_locked
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_kprobe.c:probes_profile_seq_show
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/swapfile.c:SYSC_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:__kmem_cache_create
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_next_cpu
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition_rcu_cb
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_ida.c:percpu_ida_for_each_free
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_alloc
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/iommu-common.c:iommu_tbl_pool_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - net/socket.c:socket_seq_show
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/net-sysfs.c:xps_cpus_show
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff81971b30-ffffffff81971b4d: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff819ce12f)
Location: lib/cpumask.c:16
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:init_cpu_to_node
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:_cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:load_module
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_kprobe.c:probes_profile_seq_show
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition_rcu_cb
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_ida.c:percpu_ida_for_each_free
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_alloc
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue_cpu
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/net-sysfs.c:xps_cpus_show
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff819cdf00-ffffffff819cdf1d: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a075ef)
Location: lib/cpumask.c:16
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/pti.c:pti_init
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/psi.c:update_stats
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:_cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:load_module
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:register_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:alloc_buffers
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight_rw
  - block/partition-generic.c:delete_partition_work_fn
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue_cpu
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff81a073c0-ffffffff81a073dd: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a76f5b)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_die
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/pti.c:pti_init
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:post_relocation
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight_rw
  - block/partition-generic.c:delete_partition_work_fn
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue_cpu
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff81a76d30-ffffffff81a76d4d: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81aae2b3)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_die
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:tunables_write
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:post_relocation
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight_rw
  - block/partition-generic.c:delete_partition_work_fn
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue_cpu
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_stats_put
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff81aae140-ffffffff81aae15d: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815e8010)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_next
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:impress_friends
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_die
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_all
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:hw_break_reserve_slot
  - arch/x86/kernel/kgdb.c:hw_break_reserve_slot
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:sev_map_percpu_data
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/pti.c:pti_clone_user_shared
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:make_per_cpu_thp
  - arch/x86/platform/uv/tlb_uv.c:get_cpu_topology
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu_tunables
  - arch/x86/platform/uv/tlb_uv.c:pq_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:tunables_write
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:check_enable
  - arch/x86/platform/uv/tlb_uv.c:disable_for_period
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_cleanup_mask
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:arch_set_thermal_pressure
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:init_uclamp
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:select_idle_smt
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:tell_cpu_to_push
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
  - kernel/sched/rt.c:do_balance_runtime
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:build_balance_mask
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/stats.c:schedstat_next
  - kernel/sched/debug.c:sched_debug_next
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/irqdesc.c:desc_set_defaults
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/update.c:show_stalled_ipi_trace
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
  - kernel/time/timer.c:init_timers
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:tick_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:call_function_init
  - kernel/module.c:post_relocation
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:root_cgroup_cputime
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_get_regs_helper
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/cpumap.c:cpu_map_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_event_init_all_cpus
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/core.c:perf_cgroup_ensure_storage
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:start_shepherd_timer
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:all_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:is_kernel_percpu_address
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/vmalloc.c:purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:lifetime_write_kbytes_show
  - fs/ext4/sysfs.c:session_write_kbytes_show
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_update_queue_map
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_init_cpu_queues
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:part_inflight_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_stat_read_all
  - block/partitions/core.c:hd_struct_free_work
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/iommu/iova.c:init_iova_rcaches
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_delete
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:free_policy_dbs_info
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_has_acpi_ppc
  - drivers/cpufreq/intel_pstate.c:intel_pstate_no_acpi_pss
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:sock_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/devlink.c:devlink_trap_group_register
  - net/core/devlink.c:devlink_trap_register
  - net/core/devlink.c:devlink_trap_stats_put
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:trie_show_usage
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff815e7e00-ffffffff815e7e1d: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8160d24e)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_get_topology
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_next
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:impress_friends
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_die
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_all
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:hw_break_reserve_slot
  - arch/x86/kernel/kgdb.c:hw_break_reserve_slot
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:sev_map_percpu_data
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/kernel/sev-es.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev-es.c:sev_es_init_vc_handling
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/pti.c:pti_clone_user_shared
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_cleanup_mask
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:init_uclamp
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:select_idle_smt
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:tell_cpu_to_push
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
  - kernel/sched/rt.c:do_balance_runtime
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:build_balance_mask
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/stats.c:schedstat_next
  - kernel/sched/debug.c:sched_debug_next
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/irqdesc.c:desc_set_defaults
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/update.c:show_stalled_ipi_trace
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
  - kernel/time/timer.c:init_timers
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:tick_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:call_function_init
  - kernel/module.c:post_relocation
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:root_cgroup_cputime
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_get_regs_helper
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/cpumap.c:cpu_map_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_event_init_all_cpus
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/core.c:perf_cgroup_ensure_storage
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:start_shepherd_timer
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:all_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:is_kernel_percpu_address
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/mmap_lock.c:trace_mmap_lock_reg
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/vmalloc.c:purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_enable
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_update_queue_map
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_init_cpu_queues
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:part_inflight_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_stat_read_all
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_reseed
  - lib/random32.c:prandom_init_early
  - lib/random32.c:prandom_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_cpc_valid
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/iommu/iova.c:init_iova_rcaches
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_delete
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:free_policy_dbs_info
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_has_acpi_ppc
  - drivers/cpufreq/intel_pstate.c:intel_pstate_no_acpi_pss
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:sock_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:flush_all_backlogs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/devlink.c:devlink_trap_group_register
  - net/core/devlink.c:devlink_trap_register
  - net/core/devlink.c:devlink_trap_stats_put
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:trie_show_usage
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff8160cf60-ffffffff8160cf7d: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815f06f3)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_next
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_die
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_all
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/update.c:show_stalled_ipi_trace
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:call_function_init
  - kernel/module.c:load_module
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:root_cgroup_cputime
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_get_regs_helper
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/cpumap.c:cpu_map_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:perf_cgroup_ensure_storage
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:all_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:is_kernel_percpu_address
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/mmap_lock.c:trace_mmap_lock_reg
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/vmalloc.c:purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_enable
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_update_queue_map
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:part_inflight_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_stat_read_all
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_reseed
  - lib/random32.c:prandom_init_early
  - lib/random32.c:prandom_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_cpc_valid
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_domain
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:free_policy_dbs_info
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:sock_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:flush_all_backlogs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_stats_put
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff815f09d0-ffffffff815f09f5: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8165d7d3)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/xen/enlighten.c:xen_reboot
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_next
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_die
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_all
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_unlock
  - kernel/sched/core.c:sched_core_lock
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:cpuusage_read
  - kernel/sched/cpuacct.c:cpuusage_sys_read
  - kernel/sched/cpuacct.c:cpuusage_user_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/update.c:show_stalled_ipi_trace
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:call_function_init
  - kernel/module.c:load_module
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:root_cgroup_cputime
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_get_regs_helper
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/cpumap.c:cpu_map_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:perf_cgroup_ensure_storage
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:all_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:is_kernel_percpu_address
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/mmap_lock.c:trace_mmap_lock_reg
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/vmalloc.c:purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_enable
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:flush_all_cpus_locked
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:part_inflight_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_stat_read_all
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_timer_fn
  - block/mq-deadline.c:dd_owned_by_driver
  - block/mq-deadline.c:dd_owned_by_driver
  - block/mq-deadline.c:dd_owned_by_driver
  - block/mq-deadline.c:dd_queued
  - block/mq-deadline.c:dd_queued
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_reseed
  - lib/random32.c:prandom_init_early
  - lib/random32.c:prandom_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_cpc_valid
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_domain
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/tun.c:tun_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:free_policy_dbs_info
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:sock_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:flush_all_backlogs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_stats_read
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp.c:tcp_orphan_update
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_release_dsts
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff8165db10-ffffffff8165db35: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81776ddd)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/xen/enlighten.c:xen_reboot
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/proc.c:c_next
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_die
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_all
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:hw_break_release_slot
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_lock
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_sched_dl_class
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:cpudl_init
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/sched/build_policy.c:init_sched_rt_class
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:__disable_runtime
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:cpupri_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:sched_debug_start
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:sugov_stop
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/sched/build_utility.c:cpuusage_read
  - kernel/sched/build_utility.c:cpuusage_sys_read
  - kernel/sched/build_utility.c:cpuusage_user_read
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:show_stalled_ipi_trace
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:cblist_init_generic
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__is_module_percpu_address
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:call_function_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:root_cgroup_cputime
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_get_regs_helper
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/cpumap.c:cpu_map_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:perf_cgroup_ensure_storage
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:all_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:is_kernel_percpu_address
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/mmap_lock.c:trace_mmap_lock_reg
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_enable
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:free_area_init_core_hotplug
  - mm/memory_hotplug.c:try_offline_node
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:flush_all_cpus_locked
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:part_inflight_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_stat_read_all
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:cppc_allow_fast_switch
  - drivers/acpi/cppc_acpi.c:acpi_cpc_valid
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/tun.c:tun_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:free_policy_dbs_info
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/amd-pstate.c:cppc_enable
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:sock_inuse_get
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_get_num_default_rss_queues
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_stats_read
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp.c:tcp_orphan_update
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/mib.c:mptcp_seq_show
```
**Symbols:**

```
ffffffff81777120-ffffffff81777157: cpumask_next (STB_GLOBAL)
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
In arch/x86/kernel/cpu/proc.c (ffffffff81070775)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_start
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c327)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In kernel/sched/build_policy.c (ffffffff8115a272)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
```
In kernel/sched/build_utility.c (ffffffff811702be)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_debug_start
```
```
In kernel/irq/affinity.c (ffffffff811a6034)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/rcu/update.c (ffffffff811aaac4)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811b40c6)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clocksource.c (ffffffff811e07e4)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/timer_list.c (ffffffff811e2339)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - kernel/time/timer_list.c:move_iter
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127cc79)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff813009fa)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff81353a8b)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In fs/seq_file.c (ffffffff814b31f8)
Location: include/linux/cpumask.h:175
Inline: True
```
```
In drivers/char/random.c (ffffffff81a94edb)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In lib/cpumask.c (ffffffff8201f91c)
Location: include/linux/cpumask.h:175
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_next_wrap
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
In arch/x86/kernel/cpu/proc.c (ffffffff81072375)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_start
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f467)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In kernel/sched/build_policy.c (ffffffff8116a482)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
```
In kernel/sched/build_utility.c (ffffffff8117fd0e)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_debug_start
```
```
In kernel/rcu/update.c (ffffffff811bc9f4)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811c8122)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clocksource.c (ffffffff811f4ce8)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/timer_list.c (ffffffff811f6899)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/time/timer_list.c:move_iter
```
```
In kernel/trace/trace_hwlat.c (ffffffff81294959)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8132f557)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff81384c8b)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In fs/seq_file.c (ffffffff814e8248)
Location: include/linux/cpumask.h:208
Inline: True
```
```
In lib/group_cpus.c (ffffffff818e6a6f)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/char/random.c (ffffffff81ae06fb)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In lib/cpumask.c (ffffffff8209f97c)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_next_wrap
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
In arch/x86/kernel/cpu/proc.c (ffffffff81079b95)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_start
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a68f7)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In kernel/sched/build_policy.c (ffffffff81177b42)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
```
In kernel/sched/build_utility.c (ffffffff8118d82e)
Location: include/linux/cpumask.h:208
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811cb81e)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811d9fae)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/time/clocksource.c (ffffffff8120ae3f)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/timer_list.c (ffffffff8120ca39)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/time/timer_list.c:move_iter
```
```
In kernel/trace/trace_hwlat.c (ffffffff812affb9)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81353a77)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff813ae09b)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In fs/seq_file.c (ffffffff8151c0d8)
Location: include/linux/cpumask.h:208
Inline: True
```
```
In lib/group_cpus.c (ffffffff8192da8f)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/char/random.c (ffffffff81b33afb)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In lib/cpumask.c (ffffffff8217794c)
Location: include/linux/cpumask.h:208
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_next_wrap
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffff800010d84658)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/arm64/kernel/irq.c:init_IRQ
  - arch/arm64/kernel/setup.c:topology_init
  - arch/arm64/kernel/setup.c:setup_arch
  - arch/arm64/kernel/cpuinfo.c:cpuinfo_regs_init
  - arch/arm64/kernel/cpuinfo.c:c_show
  - arch/arm64/kernel/cpuinfo.c:c_show
  - arch/arm64/kernel/smp.c:show_ipi_list
  - arch/arm64/kernel/smp.c:smp_prepare_cpus
  - arch/arm64/kernel/topology.c:parse_acpi_topology
  - arch/arm64/kernel/sdei.c:sdei_arch_get_entry_point
  - arch/arm64/kernel/sdei.c:sdei_arch_get_entry_point
  - arch/arm64/mm/context.c:check_and_switch_context
  - arch/arm64/mm/context.c:check_and_switch_context
  - arch/arm64/mm/context.c:check_and_switch_context
  - arch/arm64/mm/numa.c:setup_per_cpu_areas
  - virt/kvm/kvm_main.c:kvm_init
  - virt/kvm/arm/arm.c:kvm_arch_init
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:teardown_hyp_mode
  - virt/kvm/arm/arm.c:kvm_arch_init_vm
  - arch/arm/xen/enlighten.c:xen_guest_init
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:post_relocation
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_event_init_all_cpus
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:toggle_bp_slot
  - kernel/events/hw_breakpoint.c:toggle_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:alloc_buffers
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight_rw
  - block/partition-generic.c:delete_partition_work_fn
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_send_ipi
  - drivers/irqchip/irq-gic-v3.c:gic_raise_softirq
  - drivers/irqchip/irq-gic-v3.c:gic_raise_softirq
  - drivers/irqchip/irq-gic-v3.c:gic_raise_softirq
  - drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/base/arch_topology.c:init_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:reset_cpu_topology
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:topology_normalize_cpu_scale
  - drivers/base/arch_topology.c:topology_normalize_cpu_scale
  - drivers/base/arch_topology.c:register_cpu_capacity_sysctl
  - drivers/base/arch_topology.c:arch_set_freq_scale
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/cpuidle-arm.c:arm_idle_init
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/firmware/arm_sdei.c:sdei_event_register
  - drivers/clocksource/arm_arch_timer.c:arch_timer_check_ool_workaround
  - drivers/of/base.c:of_cpu_node_to_id
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - drivers/perf/arm_pmu.c:__armpmu_alloc
  - drivers/perf/arm_pmu.c:armpmu_count_irq_users
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
  - drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_probe
  - drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting
  - drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue_cpu
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_stats_put
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffff800010d84480-ffff800010d844a8: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (c0e7fb98)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/arm/kernel/setup.c:c_show
  - arch/arm/kernel/setup.c:topology_init
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/smp.c:cpufreq_callback
  - arch/arm/kernel/smp.c:cpufreq_callback
  - arch/arm/kernel/smp.c:show_ipi_list
  - arch/arm/kernel/smp.c:smp_cpus_done
  - arch/arm/kernel/topology.c:init_cpu_topology
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/context.c:a15_erratum_get_cpumask
  - arch/arm/mm/cache-uniphier.c:uniphier_cache_init
  - arch/arm/common/mcpm_entry.c:mcpm_sync_init
  - arch/arm/common/bL_switcher.c:bL_switcher_active_store
  - arch/arm/common/bL_switcher.c:bL_switcher_get_logical_index
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
  - arch/arm/common/bL_switcher.c:bL_switcher_restore_cpus
  - arch/arm/mach-qcom/platsmp.c:qcom_smp_prepare_cpus
  - arch/arm/mach-vexpress/spc.c:ve_spc_clk_init
  - arch/arm/mach-vexpress/platsmp.c:vexpress_smp_init_ops
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:post_relocation
  - kernel/module.c:__is_module_percpu_address
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_get_regs_helper
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:set_buffer_entries
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:toggle_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:setup_per_cpu_areas
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_writers
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight_rw
  - block/partition-generic.c:delete_partition_work_fn
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/irqchip/irq-hip04.c:hip04_raise_softirq
  - drivers/irqchip/irq-gic-v3.c:gic_raise_softirq
  - drivers/irqchip/irq-gic-v3.c:gic_raise_softirq
  - drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_mpic_send_doorbell
  - drivers/bus/arm-cci.c:cci_probe_ports
  - drivers/bus/arm-cci.c:cci_probe_ports
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/soc/qcom/spm.c:spm_dev_probe
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:reset_cpu_topology
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:topology_normalize_cpu_scale
  - drivers/base/arch_topology.c:register_cpu_capacity_sysctl
  - drivers/base/arch_topology.c:arch_set_freq_scale
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:free_policy_dbs_info
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/coupled.c:cpuidle_coupled_register_device
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_coupled_poke_others
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/cpuidle-big_little.c:bl_idle_driver_init
  - drivers/cpuidle/cpuidle-arm.c:arm_idle_init
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_warm_boot_addr
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_warm_boot_addr
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_cold_boot_addr
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/of/base.c:of_cpu_node_to_id
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - drivers/perf/arm_pmu.c:__armpmu_alloc
  - drivers/perf/arm_pmu.c:armpmu_count_irq_users
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue_cpu
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_stats_put
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field64
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
c0e7f9b0-c0e7f9d4: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (c000000000ec3900)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/powerpc/kernel/irq.c:irq_choose_cpu
  - arch/powerpc/kernel/irq.c:irq_choose_cpu
  - arch/powerpc/kernel/irq.c:arch_show_interrupts
  - arch/powerpc/kernel/irq.c:arch_show_interrupts
  - arch/powerpc/kernel/irq.c:arch_show_interrupts
  - arch/powerpc/kernel/irq.c:arch_show_interrupts
  - arch/powerpc/kernel/irq.c:arch_show_interrupts
  - arch/powerpc/kernel/irq.c:arch_show_interrupts
  - arch/powerpc/kernel/irq.c:arch_show_interrupts
  - arch/powerpc/kernel/irq.c:arch_show_interrupts
  - arch/powerpc/kernel/irq.c:arch_show_interrupts
  - arch/powerpc/kernel/irq.c:arch_show_interrupts
  - arch/powerpc/kernel/sysfs.c:topology_init
  - arch/powerpc/kernel/sysfs.c:topology_init
  - arch/powerpc/kernel/sysfs.c:cpu_remove_dev_attr_group
  - arch/powerpc/kernel/sysfs.c:cpu_remove_dev_attr
  - arch/powerpc/kernel/sysfs.c:cpu_add_dev_attr_group
  - arch/powerpc/kernel/sysfs.c:cpu_add_dev_attr
  - arch/powerpc/kernel/sysfs.c:setup_smt_snooze_delay
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_rebuild
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_teardown
  - arch/powerpc/kernel/setup-common.c:setup_arch
  - arch/powerpc/kernel/setup-common.c:c_start
  - arch/powerpc/kernel/setup-common.c:show_cpuinfo
  - arch/powerpc/kernel/setup_64.c:init_fallback_flush
  - arch/powerpc/kernel/setup_64.c:setup_per_cpu_areas
  - arch/powerpc/kernel/setup_64.c:emergency_stack_init
  - arch/powerpc/kernel/setup_64.c:irqstack_early_init
  - arch/powerpc/kernel/watchdog.c:watchdog_nmi_stop
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_cpu
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_last_cpu
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan
  - arch/powerpc/kernel/iommu.c:setup_iommu_pool_hash
  - arch/powerpc/kernel/smp.c:__cpu_disable
  - arch/powerpc/kernel/smp.c:__cpu_disable
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:crash_send_ipi
  - arch/powerpc/kernel/smp.c:crash_send_ipi
  - arch/powerpc/kernel/smp.c:tick_broadcast
  - arch/powerpc/kernel/smp.c:tick_broadcast
  - arch/powerpc/kernel/smp.c:arch_send_call_function_ipi_mask
  - arch/powerpc/kernel/smp.c:arch_send_call_function_ipi_mask
  - arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec
  - arch/powerpc/kernel/machine_kexec_64.c:kexec_prepare_cpus_wait
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node
  - arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask
  - arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask
  - arch/powerpc/sysdev/xive/native.c:xive_native_init
  - arch/powerpc/platforms/powernv/setup.c:pnv_probe
  - arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states
  - arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states
  - arch/powerpc/platforms/powernv/rng.c:__machine_initcall_powernv_rng_init
  - arch/powerpc/platforms/powernv/subcore.c:set_subcores_per_core
  - arch/powerpc/platforms/powernv/subcore.c:cpu_update_split_mode
  - arch/powerpc/platforms/powernv/subcore.c:cpu_update_split_mode
  - arch/powerpc/platforms/powernv/subcore.c:cpu_update_split_mode
  - arch/powerpc/platforms/powernv/subcore.c:update_subcore_sibling_mask
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_core_pmu_counters
  - arch/powerpc/platforms/powernv/vas.c:vas_probe
  - arch/powerpc/platforms/powernv/vas.c:vas_probe
  - arch/powerpc/platforms/powernv/vas.c:chip_to_vas_id
  - arch/powerpc/platforms/pseries/lpar.c:__machine_initcall_pseries_vpa_debugfs_init
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
  - arch/powerpc/platforms/pseries/lpar.c:reset_global_dtl_mask
  - arch/powerpc/platforms/pseries/lpar.c:free_dtl_buffers
  - arch/powerpc/platforms/pseries/lpar.c:free_dtl_buffers
  - arch/powerpc/platforms/pseries/lpar.c:alloc_dtl_buffers
  - arch/powerpc/platforms/pseries/lpar.c:alloc_dtl_buffers
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
  - arch/powerpc/platforms/pseries/smp.c:smp_init_pseries
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:__machine_initcall_pseries_pseries_cpu_hotplug_init
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_online_cpu
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/dtl.c:__machine_initcall_pseries_dtl_init
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:cleanup_all_trace_imc_memory
  - arch/powerpc/perf/imc-pmu.c:cleanup_all_trace_imc_memory
  - arch/powerpc/perf/imc-pmu.c:cleanup_all_thread_imc_memory
  - arch/powerpc/perf/imc-pmu.c:cleanup_all_thread_imc_memory
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:post_relocation
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:toggle_bp_slot
  - kernel/events/hw_breakpoint.c:toggle_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight_rw
  - block/partition-generic.c:delete_partition_work_fn
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_reboot_notifier
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/of/base.c:of_cpu_node_to_id
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue_cpu
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/drop_monitor.c:exit_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_stats_put
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
c000000000ec3630-c000000000ec3674: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffe0008aeb1a)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/riscv/kernel/cpu.c:c_next
  - arch/riscv/kernel/smpboot.c:smp_prepare_cpus
  - arch/riscv/kernel/smp.c:show_ipi_stats
  - arch/riscv/kernel/smp.c:send_ipi_mask
  - arch/riscv/kernel/smp.c:riscv_cpuid_to_hartid_mask
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:do_balance_runtime
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:load_module
  - kernel/module.c:__is_module_percpu_address
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:register_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:pcpu_copy_value
  - kernel/bpf/hashtab.c:pcpu_copy_value
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sum_vm_events
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:setup_per_cpu_areas
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight_rw
  - block/partition-generic.c:delete_partition_work_fn
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_mask
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_unmask
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/arch_topology.c:init_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:reset_cpu_topology
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:topology_normalize_cpu_scale
  - drivers/base/arch_topology.c:register_cpu_capacity_sysctl
  - drivers/base/arch_topology.c:arch_set_freq_scale
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/of/base.c:of_cpu_node_to_id
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue_cpu
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_stats_put
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffe0008ae9ca-ffffffe0008ae9ee: cpumask_next (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a4d103)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_die
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/pti.c:pti_init
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:post_relocation
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight_rw
  - block/partition-generic.c:delete_partition_work_fn
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue_cpu
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_stats_put
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff81a4cf90-ffffffff81a4cfad: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a0a233)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_die
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/pti.c:pti_init
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/time/tick-sched.c:tick_nohz_init
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:post_relocation
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight_rw
  - block/partition-generic.c:delete_partition_work_fn
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/vxlan.c:vxlan_init
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/hv/vmbus_drv.c:vmbus_exit
  - drivers/hv/hv.c:hv_synic_free
  - drivers/hv/hv.c:hv_synic_alloc
  - drivers/hv/hv.c:hv_synic_alloc
  - drivers/hv/channel_mgmt.c:vmbus_initiate_unload
  - drivers/hv/channel_mgmt.c:vmbus_initiate_unload
  - drivers/hv/channel_mgmt.c:init_vp_index
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue_cpu
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_stats_put
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/ipv4/ip_tunnel.c:ip_tunnel_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff81a0a0c0-ffffffff81a0a0dd: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ab94f3)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_die
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/pti.c:pti_init
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:post_relocation
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight_rw
  - block/partition-generic.c:delete_partition_work_fn
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue_cpu
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_stats_put
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_net
  - net/netfilter/nf_conntrack_ecache.c:ecache_work
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff81ab9380-ffffffff81ab939d: cpumask_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int cpumask_next(int n, const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ac5943)
Location: lib/cpumask.c:17
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/amd.c:threshold_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_die
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:tunables_write
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_next_cpu
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_spawn_core_kthreads
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:post_relocation
  - kernel/module.c:__is_module_percpu_address
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/stackmap.c:stack_map_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight_rw
  - block/partition-generic.c:delete_partition_work_fn
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/node.c:__register_one_node
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_queue_cpu
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_stats_put
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff81ac57d0-ffffffff81ac57ed: cpumask_next (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
