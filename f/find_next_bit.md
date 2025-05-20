# Function: <code>find_next_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff813fdfd0)
Location: lib/find_bit.c:61
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/cqm.c:intel_cqm_cpu_notifier
  - arch/x86/events/intel/cqm.c:intel_cqm_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/rapl.c:rapl_cpu_init
  - arch/x86/events/intel/rapl.c:rapl_pmu_init
  - arch/x86/events/intel/rapl.c:rapl_cpu_notifier
  - arch/x86/events/intel/uncore.c:uncore_cpu_starting
  - arch/x86/events/intel/uncore.c:uncore_cpu_notifier
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
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
  - arch/x86/kernel/irqinit.c:vector_used_by_percpu_irq
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/numa.c:numa_set_distance
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/softirq.c:softirq_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/pid.c:next_pidmap
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/smpboot.c:idle_threads_init
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
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/clock.c:sched_clock_init
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:cpuusage_read
  - kernel/locking/lglock.c:lg_global_lock
  - kernel/locking/lglock.c:lg_global_unlock
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/rcu/srcu.c:cleanup_srcu_struct
  - kernel/rcu/srcu.c:try_check_zero
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/time/timer.c:timers_update_migration
  - kernel/time/timer.c:init_timers
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/time/timer_stats.c:tstats_write
  - kernel/time/timer_stats.c:init_timer_stats
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:call_function_init
  - kernel/smp.c:smp_init
  - kernel/module.c:is_module_percpu_address
  - kernel/module.c:load_module
  - kernel/cgroup.c:cgroup_calc_child_subsys_mask
  - kernel/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_can_fork
  - kernel/cgroup.c:cgroup_post_fork
  - kernel/cgroup.c:cgroup_exit
  - kernel/cgroup.c:cgroup_free
  - kernel/cpuset.c:cpuset_spread_node
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_late_setup_files
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:rb_cpu_notify
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
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
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
  - kernel/padata.c:padata_index_to_cpu
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:kswapd_init
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:sum_vm_events
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:vmstat_cpuup_callback
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/percpu.c:pcpu_next_unpop
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:is_kernel_percpu_address
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:list_lru_destroy
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vm_unmap_aliases
  - mm/vmalloc.c:vmalloc_init
  - mm/swapfile.c:SyS_swapon
  - mm/frontswap.c:frontswap_register_ops
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/hugetlb.c:next_node_allowed
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memory-failure.c:memory_failure_init
  - mm/page_isolation.c:alloc_migrate_target
  - mm/zsmalloc.c:zs_unregister_cpu_notifier
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:get_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:proc_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/buffer.c:free_more_memory
  - fs/locks.c:filelock_init
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/apparmor/lsm.c:destroy_buffers
  - security/apparmor/lsm.c:alloc_buffers
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-iopoll.c:blk_iopoll_setup
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq-tag.c:bt_tags_for_each
  - block/blk-mq-tag.c:bt_for_each
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
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
  - lib/cpumask.c:cpumask_next_and
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_any_but
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - lib/random32.c:prandom_seed
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed_full_state
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_remap
  - lib/percpu-refcount.c:__percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_for_each_free
  - lib/percpu_ida.c:percpu_ida_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/percpu_counter.c:percpu_counter_set
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/iommu-common.c:iommu_tbl_pool_init
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/gpio/gpio-zx.c:zx_irq_handler
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_devices_uninit
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed
  - drivers/acpi/processor_throttling.c:cpumask_next
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_perflib.c:cpumask_next
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:free_cache_attributes
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:register_one_node
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_set_affinity
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_register_device
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_exit
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate
  - drivers/cpufreq/cpufreq_governor.c:dbs_check_cpu
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msrs
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:pid_param_set
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_exit
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/socket.c:socket_seq_show
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:__gnet_stats_copy_basic_cpu
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:netif_reset_xps_queues_gt
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/flow.c:flow_cache_new_hashrnd
  - net/core/flow.c:flow_cache_fini
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_flush
  - net/core/net-sysfs.c:show_xps_map
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/ipv6/route.c:ip6_dst_alloc
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_init
```
**Symbols:**

```
ffffffff813fdfd0-ffffffff813fdfeb: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81445630)
Location: lib/find_bit.c:61
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
  - arch/x86/xen/enlighten.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
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
  - arch/x86/kernel/irqinit.c:vector_used_by_percpu_irq
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
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
  - arch/x86/kernel/smpboot.c:smp_init_package_map
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:numa_set_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/softirq.c:softirq_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/pid.c:next_pidmap
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
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
  - kernel/sched/clock.c:sched_clock_init
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/locking/lglock.c:lg_global_unlock
  - kernel/locking/lglock.c:lg_global_lock
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/nmi.c:printk_nmi_init
  - kernel/printk/nmi.c:printk_nmi_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_mask
  - kernel/rcu/srcu.c:try_check_zero
  - kernel/rcu/srcu.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:timers_update_migration
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/time/timer_stats.c:init_timer_stats
  - kernel/time/timer_stats.c:tstats_write
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:load_module
  - kernel/module.c:is_module_percpu_address
  - kernel/cgroup.c:cgroup_free
  - kernel/cgroup.c:cgroup_exit
  - kernel/cgroup.c:cgroup_post_fork
  - kernel/cgroup.c:cgroup_can_fork
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_propagate_control
  - kernel/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:rebind_subsystems
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/ring_buffer.c:rb_cpu_notify
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
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
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
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
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:perf_output_sample_regs
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
  - kernel/padata.c:padata_index_to_cpu
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
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
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:vmstat_cpuup_callback
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_next_unpop
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/list_lru.c:list_lru_destroy
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:vm_unmap_aliases
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_init
  - mm/swapfile.c:SyS_swapon
  - mm/frontswap.c:frontswap_register_ops
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_pool_create
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:do_migrate_pages
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memory-failure.c:memory_failure_init
  - mm/zsmalloc.c:zs_unregister_cpu_notifier
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/buffer.c:free_more_memory
  - fs/locks.c:filelock_init
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/apparmor/lsm.c:alloc_buffers
  - security/apparmor/lsm.c:destroy_buffers
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq-tag.c:bt_tags_for_each
  - block/blk-mq-tag.c:bt_for_each
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
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
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_any_but
  - lib/cpumask.c:cpumask_next_and
  - lib/nodemask.c:__next_node_in
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/percpu-refcount.c:__percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_ida.c:percpu_ida_for_each_free
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/iommu-common.c:iommu_tbl_pool_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/gpio/gpio-zx.c:zx_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/host/pcie-designware.c:dw_handle_msi_irq
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:rand_initialize
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:queue_flush_all
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_exit
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:free_cache_attributes
  - drivers/base/node.c:register_one_node
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
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
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msrs
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:pid_param_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpuidle/cpuidle.c:cpuidle_register
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/socket.c:socket_seq_show
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues_gt
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/flow.c:flow_cache_fini
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_new_hashrnd
  - net/core/net-sysfs.c:show_xps_map
  - net/core/dst_cache.c:dst_cache_destroy
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_dst_alloc
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_init
  - net/ncsi/ncsi-manage.c:ncsi_find_filter
```
**Symbols:**

```
ffffffff81445630-ffffffff8144564b: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81463e20)
Location: lib/find_bit.c:61
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
  - arch/x86/xen/enlighten.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
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
  - arch/x86/kernel/irqinit.c:vector_used_by_percpu_irq
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_init_device
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
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
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:next_pidmap
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
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
  - kernel/sched/clock.c:sched_clock_init
  - kernel/sched/fair.c:show_numa_stats
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
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:__cpuusage_read
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/nmi.c:printk_nmi_init
  - kernel/printk/nmi.c:printk_nmi_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/rcu/srcu.c:try_check_zero
  - kernel/rcu/srcu.c:cleanup_srcu_struct
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
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/timer.c:init_timers
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:timers_update_migration
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/time/timer_stats.c:init_timer_stats
  - kernel/time/timer_stats.c:tstats_write
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:call_function_init
  - kernel/module.c:load_module
  - kernel/module.c:is_module_percpu_address
  - kernel/cgroup.c:cgroup_free
  - kernel/cgroup.c:cgroup_exit
  - kernel/cgroup.c:cgroup_post_fork
  - kernel/cgroup.c:cgroup_can_fork
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_propagate_control
  - kernel/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:rebind_subsystems
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_pid_open
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
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
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
  - kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:perf_output_sample_regs
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
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:drain_all_pages
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_add_drain_all
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
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
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_next_unpop
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/list_lru.c:list_lru_destroy
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/swapfile.c:SyS_swapon
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:do_migrate_pages
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/buffer.c:free_more_memory
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_process_rq_list
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-sysfs.c:blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
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
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_any_but
  - lib/cpumask.c:cpumask_next_and
  - lib/nodemask.c:__next_node_in
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_ida.c:percpu_ida_for_each_free
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_alloc
  - lib/genalloc.c:gen_pool_best_fit
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_set
  - lib/iommu-common.c:iommu_tbl_pool_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/host/pcie-designware.c:dw_handle_msi_irq
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:rand_initialize
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:queue_flush_all
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_exit
  - drivers/base/cacheinfo.c:free_cache_attributes
  - drivers/base/node.c:register_one_node
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
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
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:pid_param_set
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
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/flow.c:flow_cache_fini
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_new_hashrnd
  - net/core/net-sysfs.c:show_xps_map
  - net/core/dst_cache.c:dst_cache_destroy
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_dst_alloc
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_init
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ncsi/ncsi-manage.c:ncsi_find_filter
```
**Symbols:**

```
ffffffff81463e20-ffffffff81463e3b: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81468ec0)
Location: lib/find_bit.c:61
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
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
  - arch/x86/kernel/irqinit.c:vector_used_by_percpu_irq
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__check_limbo
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
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
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/softirq.c:softirq_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:next_pidmap
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
  - kernel/sched/fair.c:show_numa_stats
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
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_next_push_cpu
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
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sysrq_sched_debug_show
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
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
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
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
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
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
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
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
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
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:perf_output_sample_regs
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
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:drop_slab
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
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sum_vm_events
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_next_unpop
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/swapfile.c:SyS_swapon
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmem_cache_create
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/buffer.c:free_more_memory
  - fs/locks.c:filelock_init
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/apparmor/lsm.c:destroy_buffers
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_next_cpu
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu_ida.c:percpu_ida_for_each_free
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_alloc
  - lib/genalloc.c:gen_pool_best_fit
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
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
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
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/char/random.c:rand_initialize
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:queue_flush_timeout
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_exit
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_read_distance
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:loopback_get_stats64
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
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
  - drivers/cpufreq/intel_pstate.c:pid_param_set
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
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/flow.c:flow_cache_fini
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_new_hashrnd
  - net/core/net-sysfs.c:show_xps_map
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
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
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_dst_alloc
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ncsi/ncsi-manage.c:ncsi_find_filter
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/cpumask.c:cpumask_next_and
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff81468ec0-ffffffff81468ecd: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81495190)
Location: lib/find_bit.c:61
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__check_limbo
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/bpf/devmap.c:__dev_map_flush
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/events/core.c:perf_output_sample_regs
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/slub.c:__kmem_cache_create
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:rand_initialize
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/node.c:node_read_distance
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_find_filter
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/cpumask.c:cpumask_next_and
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff81495190-ffffffff8149519d: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814ca510)
Location: lib/find_bit.c:71
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__check_limbo
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/bpf/devmap.c:__dev_map_flush
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/events/core.c:perf_output_sample_regs
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/node.c:node_read_distance
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff814ca510-ffffffff814ca571: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814df230)
Location: lib/find_bit.c:71
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/bpf/devmap.c:__dev_map_flush
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/events/core.c:perf_output_sample_regs
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/node.c:node_read_distance
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff814df230-ffffffff814df291: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8150b0a0)
Location: lib/find_bit.c:67
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/events/core.c:perf_output_sample_regs
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/soundwire/bus.c:sdw_handle_slave_alerts
  - drivers/soundwire/bus.c:sdw_handle_slave_alerts
  - drivers/soundwire/bus.c:sdw_handle_slave_alerts
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff8150b0a0-ffffffff8150b0fb: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81528ec0)
Location: lib/find_bit.c:67
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/events/core.c:perf_output_sample_regs
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:s_show
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81528ec0-ffffffff81528f1b: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8158c7d0)
Location: lib/find_bit.c:75
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_clump8
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:get_nodes_in_cpumask
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/events/core.c:perf_output_sample_regs
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:s_show
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/slub.c:init_kmem_cache_nodes
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_alloc_shrinker_maps
  - mm/memcontrol.c:memcg_expand_one_shrinker_map
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/io-wq.c:__io_wq_destroy
  - fs/io-wq.c:__io_wq_destroy
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_cancel_all
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
  - fs/proc/task_mmu.c:show_numa_map
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_destroy
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-msic.c:msic_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
```
**Symbols:**

```
ffffffff8158c820-ffffffff8158c836: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815a924f)
Location: lib/find_bit.c:77
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_clump8
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:icl_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/debug.c:sd_ctl_doflags
  - kernel/sched/debug.c:sd_ctl_doflags
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:get_nodes_in_cpumask
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/events/core.c:perf_output_sample_regs
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:s_show
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:allowed_mems_nr
  - mm/hugetlb.c:hugetlb_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/slub.c:init_kmem_cache_nodes
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_alloc_shrinker_maps
  - mm/memcontrol.c:memcg_expand_one_shrinker_map
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/io-wq.c:io_wq_cpu_online
  - fs/io-wq.c:__io_wq_destroy
  - fs/io-wq.c:__io_wq_destroy
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
  - fs/proc/task_mmu.c:show_numa_map
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_destroy
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-msic.c:msic_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - net/core/dev.c:dev_change_proto_down_reason
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/devlink.c:__devlink_reload_stats_update
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
```
**Symbols:**

```
ffffffff815a9290-ffffffff815a92a6: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008c5e)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
```
```
In arch/x86/events/amd/core.c (ffffffff81009b9e)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b7a8)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff831bc799)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
```
```
In arch/x86/events/intel/ds.c (ffffffff8101298f)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
```
```
In arch/x86/events/intel/knc.c (ffffffff810145b7)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101b438)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81020726)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff831bf85c)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/topology.c (ffffffff831c892f)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054bd1)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810628b7)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81062fcd)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106ea8e)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
```
In arch/x86/kernel/apic/vector.c (ffffffff831d5281)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bc98db)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff831de45b)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff81bcc25c)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:__next_node
```
```
In arch/x86/mm/amdtopology.c (ffffffff831e007d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/sysctl.c (ffffffff810af164)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/workqueue.c (ffffffff810c3b70)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/fair.c (ffffffff810f73dc)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff811034f3)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/debug.c (ffffffff81106534)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/sched/debug.c:sd_flags_show
```
```
In kernel/power/snapshot.c (ffffffff81114bab)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/power/snapshot.c:memory_bm_next_pfn
```
```
In kernel/irq/irqdesc.c (ffffffff8111e165)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_next_irq
```
```
In kernel/irq/affinity.c (ffffffff81129f6c)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/rcu/tree.c (ffffffff81130de2)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/time/timer.c (ffffffff811417ae)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
```
```
In kernel/cgroup/cgroup.c (ffffffff8117543d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/cgroup/rdma.c (ffffffff8117a90e)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/trace/trace.c (ffffffff811bda8f)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace.c:trace_pid_start
```
```
In kernel/bpf/verifier.c (ffffffff81208f5c)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffffffff8123fe48)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
```
```
In mm/oom_kill.c (ffffffff812651c5)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff831efd61)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
Direct callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/mmzone.c (ffffffff8128349d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff831eff92)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/percpu.c (ffffffff8128ae89)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
```
In mm/compaction.c (ffffffff81290211)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81295461)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812ba890)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff812bf4b9)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/swapfile.c (ffffffff812cda82)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/frontswap.c (ffffffff812d33dd)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (ffffffff812d9eb2)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff812deeaf)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/slub.c (ffffffff812f2003)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff81308193)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_lruvec_page_state
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In fs/dcache.c (ffffffff813454af)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/io-wq.c (ffffffff813a22d6)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_cpu_online
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_cancel_cb
```
```
In fs/proc/task_mmu.c (ffffffff813ced6b)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff813e2ed4)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff814264ff)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In security/selinux/ss/ebitmap.c (ffffffff814e3629)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff814e7e54)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814f02a8)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff814f3f72)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
```
In block/blk-mq.c (ffffffff81575bb0)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff81579ae1)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
```
In lib/bitmap.c (ffffffff815a9631)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/bitmap.c:bitmap_find_next_zero_area_off
```
```
In lib/find_bit.c (ffffffff815b3e24)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_clump8
```
```
In lib/genalloc.c (ffffffff815c245c)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_destroy
  - lib/genalloc.c:gen_pool_destroy
```
```
In lib/cpumask.c (ffffffff815f0704)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
```
```
In lib/nodemask.c (ffffffff815f54fa)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
```
In lib/vsprintf.c (ffffffff815fdc9d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
```
In lib/xarray.c (ffffffff81603ce2)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8160f91f)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81612615)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81613b6a)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff8161564e)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
```
```
In drivers/gpio/gpiolib.c (ffffffff81617ecb)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81622ee3)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/search.c (ffffffff81637b68)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pcie/rcec.c (ffffffff8164280d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff81beb01c)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165eca5)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/acpi/sysfs.c (ffffffff8320aa53)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
```
In drivers/acpi/x86/apple.c (ffffffff8169bbc3)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa/hmat.c (ffffffff816e6d2d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/pnp/manager.c (ffffffff816f5456)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_irq
```
```
In drivers/dma/dmaengine.c (ffffffff817056e9)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
Direct callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff8170990f)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
```
```
In drivers/xen/balloon.c (ffffffff8320f2d3)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81bf80f9)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/tty/n_tty.c (ffffffff817396eb)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
```
In drivers/tty/vt/keyboard.c (ffffffff817481a9)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
```
```
In drivers/tty/vt/vt.c (ffffffff8175151d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/char/random.c (ffffffff81770ff3)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/hpet.c (ffffffff81775de2)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_timer_set_irq
```
```
In drivers/iommu/intel/iommu.c (ffffffff81793f99)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff817d0eaa)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817dd9a4)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/block/xen-blkfront.c (ffffffff817e8f1d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/nvdimm/core.c (ffffffff818008f1)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8180458e)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:commands_show
```
```
In drivers/nvdimm/label.c (ffffffff8180f91f)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff81832a03)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d83a9)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci-hub.c (ffffffff819047ac)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81907ffb)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/input/input.c (ffffffff819141d8)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (ffffffff81917e62)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/misc/uinput.c (ffffffff81920d1d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8193226f)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In net/core/dev.c (ffffffff819e7b36)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down_reason
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/devlink.c (ffffffff81a4a337)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_reload_stats_update
```
```
In net/ethtool/ioctl.c (ffffffff81a75361)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba1d3b)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba2e10)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
**Symbols:**

```
ffffffff812730e0-ffffffff812730f9: find_next_bit.part.0 (STB_LOCAL)
ffffffff81beb01c-ffffffff81beb035: find_next_bit (STB_LOCAL)
ffffffff81bf5df5-ffffffff81bf5e1f: find_next_bit.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009ada)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
```
```
In arch/x86/events/amd/core.c (ffffffff8100ac33)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100bc9d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8329cb1a)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
```
```
In arch/x86/events/intel/ds.c (ffffffff81013e10)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
```
```
In arch/x86/events/intel/knc.c (ffffffff81015941)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101ddb6)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024383)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8329fde8)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/topology.c (ffffffff832a9b6d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105d521)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106c757)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106ce57)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107a40e)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
```
In arch/x86/kernel/apic/vector.c (ffffffff832b7db3)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc51e)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff832c16e9)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff81ca2245)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff832c36c6)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/sysctl.c (ffffffff810c18f9)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/workqueue.c (ffffffff810d6710)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
Direct callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff8111194c)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff81120328)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/debug.c (ffffffff811241e4)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/sched/debug.c:sd_flags_show
```
```
In kernel/power/snapshot.c (ffffffff81134d18)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/power/snapshot.c:memory_bm_next_pfn
```
```
In kernel/irq/irqdesc.c (ffffffff8113e5e5)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_next_irq
```
```
In kernel/irq/affinity.c (ffffffff8114a8cc)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/rcu/tree.c (ffffffff81152a47)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/time/timer.c (ffffffff81164c6e)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
```
```
In kernel/cgroup/cgroup.c (ffffffff8119c999)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/cgroup/rdma.c (ffffffff811a2275)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/trace/trace.c (ffffffff811e85df)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace.c:trace_pid_start
```
```
In kernel/bpf/verifier.c (ffffffff8123ca52)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffffffff8127a6e8)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
```
```
In mm/oom_kill.c (ffffffff812a19f2)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff832d54d7)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
Direct callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/mmzone.c (ffffffff812c169d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff832d5724)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/percpu.c (ffffffff812ca08d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
```
In mm/compaction.c (ffffffff812d0251)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
Direct callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/list_lru.c (ffffffff812d59a1)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812fce90)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff813090d9)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
Direct callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff81312e71)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
Direct callers:
  - mm/swapfile.c:swapfile_init
```
```
In mm/frontswap.c (ffffffff81318e5d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (ffffffff81320ab0)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff813266e2)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
Direct callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffffffff8133afb9)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/migrate.c (ffffffff8133e301)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__disable_all_migrate_targets
```
```
In mm/memcontrol.c (ffffffff81353988)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
Direct callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/dcache.c (ffffffff813930bf)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/io-wq.c (ffffffff813f33f7)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_max_workers
  - fs/io-wq.c:io_wq_cpu_affinity
  - fs/io-wq.c:__io_wq_cpu_online
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_cancel_cb
```
```
In fs/proc/task_mmu.c (ffffffff81420119)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff814349e4)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8147a195)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In security/selinux/ss/ebitmap.c (ffffffff8153ca19)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff81541794)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8154a812)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8154e918)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
```
In block/blk-mq.c (ffffffff815da0ee)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff815dedfa)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
```
In lib/bitmap.c (ffffffff816127b1)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/bitmap.c:bitmap_find_next_zero_area_off
```
```
In lib/find_bit.c (ffffffff8161a028)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_clump8
```
```
In lib/genalloc.c (ffffffff8162a38c)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_destroy
  - lib/genalloc.c:gen_pool_destroy
```
```
In lib/cpumask.c (ffffffff8165d7e4)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
```
```
In lib/nodemask.c (ffffffff8166296a)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In lib/vsprintf.c (ffffffff8166b96d)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
```
In lib/xarray.c (ffffffff8166fed0)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8167e910)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8168180e)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81682ccd)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81684910)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
```
```
In drivers/gpio/gpiolib.c (ffffffff8168714b)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff8169264b)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/search.c (ffffffff816a7dfc)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pcie/rcec.c (ffffffff816b350f)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff81ce6069)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d1865)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/acpi/sysfs.c (ffffffff832f2f78)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
```
In drivers/acpi/x86/apple.c (ffffffff81711a78)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa/hmat.c (ffffffff81760300)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/pnp/manager.c (ffffffff8176fa2e)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_irq
```
```
In drivers/dma/dmaengine.c (ffffffff81780fed)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
Direct callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff817852c4)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
```
```
In drivers/xen/balloon.c (ffffffff832f822b)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81cf7231)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/regulator/irq_helpers.c (ffffffff817b2473)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/tty/n_tty.c (ffffffff817ba1aa)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
```
In drivers/tty/vt/keyboard.c (ffffffff817c93fe)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
```
```
In drivers/tty/vt/vt.c (ffffffff817d45e8)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/char/random.c (ffffffff817f6b46)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/hpet.c (ffffffff817fbb52)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_timer_set_irq
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181bdee)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff8185b84a)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81869438)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/block/xen-blkfront.c (ffffffff818752bd)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/nvdimm/core.c (ffffffff8188acf1)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e70e)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:commands_show
```
```
In drivers/nvdimm/label.c (ffffffff81899e6f)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff818bea53)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff819731c5)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci-hub.c (ffffffff819a4eb9)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819a8826)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/input/input.c (ffffffff819b62e6)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (ffffffff819ba0d2)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/misc/uinput.c (ffffffff819c3ab0)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d55b3)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In net/core/dev.c (ffffffff81a98f2f)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down_reason
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/devlink.c (ffffffff81b02397)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_reload_stats_update
```
```
In net/ethtool/ioctl.c (ffffffff81b30541)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
```
```
In net/ncsi/ncsi-manage.c (ffffffff81c6f795)
Location: include/asm-generic/bitops/find.h:23
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c70960)
Location: include/asm-generic/bitops/find.h:23
Inline: True
```
**Symbols:**

```
ffffffff81ca2245-ffffffff81ca2260: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff81ca5037-ffffffff81ca5059: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff812b0410-ffffffff812b0429: find_next_bit.part.0 (STB_LOCAL)
ffffffff812d0210-ffffffff812d022b: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff813015b0-ffffffff813015cb: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff81311e80-ffffffff81311ea2: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff813262b0-ffffffff813262cb: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff81351340-ffffffff8135135b: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff81cf3dd4-ffffffff81cf3dfe: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff819d4e90-ffffffff819d4ebe: find_next_bit.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009195)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
```
```
In arch/x86/events/amd/core.c (ffffffff8100a5cf)
Location: include/linux/find.h:31
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c9a5)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8344b522)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
Direct callers:
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
```
```
In arch/x86/events/intel/ds.c (ffffffff8101542b)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
```
```
In arch/x86/events/intel/knc.c (ffffffff8101796a)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102080b)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102810d)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8344eb6f)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8105664c)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81069a17)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079b0f)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8107a349)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8108942b)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_pending_intr_clear
  - arch/x86/kernel/apic/apic.c:apic_pending_intr_clear
  - arch/x86/kernel/apic/apic.c:apic_pending_intr_clear
  - arch/x86/kernel/apic/apic.c:apic_pending_intr_clear
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83469a6a)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346de4e)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff83473d7c)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff81e518ef)
Location: include/linux/find.h:31
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff83475f5b)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/sysctl.c (ffffffff810d90cc)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/workqueue.c (ffffffff810f02fc)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
Direct callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff8112dbcd)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/build_utility.c (ffffffff8347d727)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sd_flags_show
  - kernel/sched/build_utility.c:sd_flags_show
  - kernel/sched/build_utility.c:housekeeping_init
Direct callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/power/snapshot.c (ffffffff81156fb5)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/power/snapshot.c:memory_bm_next_pfn
```
```
In kernel/irq/irqdesc.c (ffffffff81161b75)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_next_irq
```
```
In kernel/irq/irq_sim.c (ffffffff8116c2a9)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/affinity.c (ffffffff8116ff02)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/rcu/tree.c (ffffffff8117aed0)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/time/timer.c (ffffffff811987e2)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
```
```
In kernel/cgroup/cgroup.c (ffffffff811ccc19)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/cgroup/rdma.c (ffffffff811d2c7d)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/trace/pid_list.c (ffffffff8122b868)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_next
```
```
In kernel/bpf/verifier.c (ffffffff8127fdb2)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffffffff812cded9)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/core.c:perf_output_sample_regs
```
```
In mm/oom_kill.c (ffffffff812f98da)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff83489d08)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
Direct callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/mmzone.c (ffffffff8131e73f)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff83489f7d)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/percpu.c (ffffffff813271e8)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
```
In mm/compaction.c (ffffffff8132ed09)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
Direct callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/list_lru.c (ffffffff81335336)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff81360874)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff813715b6)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
Direct callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff8137dab4)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
Direct callers:
  - mm/swapfile.c:swapfile_init
```
```
In mm/hugetlb.c (ffffffff8138d78d)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
Direct callers:
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff81395828)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
Direct callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffffffff813ad33e)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:kmem_cache_init
```
```
In mm/migrate.c (ffffffff813b11c3)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__disable_all_migrate_targets
```
```
In mm/memcontrol.c (ffffffff813cb9ca)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
Direct callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In mm/hugetlb_cgroup.c (ffffffff813d7447)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff814147df)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81498084)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff814aeb3b)
Location: include/linux/find.h:31
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff814fc421)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In security/selinux/ss/ebitmap.c (ffffffff815d43a5)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff815d992e)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff815e3536)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff815e7a01)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
```
In security/landlock/fs.c (ffffffff8163af33)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
```
```
In block/blk-mq.c (ffffffff81687bad)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff8168d316)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
```
In io_uring/io-wq.c (ffffffff816dbf77)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:__io_wq_cpu_online
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_cancel_cb
```
```
In lib/bitmap.c (ffffffff816dec0b)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/bitmap.c:bitmap_find_next_zero_area_off
```
```
In lib/find_bit.c (ffffffff816e75ad)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_clump8
```
```
In lib/genalloc.c (ffffffff816fb6d0)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
```
```
In lib/cpumask.c (ffffffff81776ddd)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
```
```
In lib/nodemask.c (ffffffff8177c7e9)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In lib/vsprintf.c (ffffffff8178584d)
Location: include/linux/find.h:31
Inline: True
```
```
In lib/xarray.c (ffffffff8178cac1)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8179add3)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179c7d6)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179ed15)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a0ff3)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
```
```
In drivers/gpio/gpiolib.c (ffffffff817a5174)
Location: include/linux/find.h:31
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (ffffffff817b23e8)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff817b3088)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/search.c (ffffffff817ca8e8)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pcie/rcec.c (ffffffff817d68d4)
Location: include/linux/find.h:31
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff817da056)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
Direct callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa92c)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/acpi/sysfs.c (ffffffff834ab002)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
```
In drivers/acpi/x86/apple.c (ffffffff81840acf)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa/hmat.c (ffffffff81893cda)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/pnp/manager.c (ffffffff818a4e62)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_irq
```
```
In drivers/dma/dmaengine.c (ffffffff818b7775)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
Direct callers:
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bbe2b)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
```
```
In drivers/xen/grant-table.c (ffffffff818c7549)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_seq
```
```
In drivers/xen/balloon.c (ffffffff834b094a)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81ebeb43)
Location: include/linux/find.h:31
Inline: True
Direct callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/regulator/irq_helpers.c (ffffffff818edda6)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/tty/n_tty.c (ffffffff818f62ce)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
```
In drivers/tty/vt/keyboard.c (ffffffff819074e5)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
```
```
In drivers/tty/vt/vt.c (ffffffff819126d0)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/char/hpet.c (ffffffff8193a93e)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/char/hpet.c:hpet_timer_set_irq
```
```
In drivers/iommu/intel/iommu.c (ffffffff834b8596)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff834baadc)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_read_distance
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff819b1fed)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/block/xen-blkfront.c (ffffffff819ba1af)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/nvdimm/core.c (ffffffff819d43e0)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7d33)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:commands_show
```
```
In drivers/nvdimm/label.c (ffffffff819e2d23)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff81a0ae01)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81acea31)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81b02834)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81b072e0)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/input/input.c (ffffffff81b15a7c)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_release_keys
  - drivers/input/input.c:input_dev_release_keys
  - drivers/input/input.c:input_dev_release_keys
  - drivers/input/input.c:input_dev_release_keys
```
```
In drivers/input/ff-core.c (ffffffff81b1a0af)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/misc/uinput.c (ffffffff81b2450e)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b37f9d)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In net/core/dev.c (ffffffff81c1dfda)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down_reason
  - net/core/dev.c:dev_change_proto_down_reason
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/devlink.c (ffffffff81c85dbb)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_reload_stats_update
  - net/core/devlink.c:__devlink_reload_stats_update
```
```
In net/ethtool/ioctl.c (ffffffff81cbb2b2)
Location: include/linux/find.h:31
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e14570)
Location: include/linux/find.h:31
Inline: True
```
**Symbols:**

```
ffffffff81e44db4-ffffffff81e44ddf: find_next_bit (STB_LOCAL)
ffffffff810556a0-ffffffff810556e0: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff81e518ef-ffffffff81e5191c: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff81e54915-ffffffff81e54949: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff81e5788b-ffffffff81e578b6: find_next_bit (STB_LOCAL)
ffffffff8130bcc0-ffffffff8130bceb: find_next_bit.part.0 (STB_LOCAL)
ffffffff8132ec60-ffffffff8132ec8d: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff81368dc0-ffffffff81368ded: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff8137d0b0-ffffffff8137d0e4: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff81e7154d-ffffffff81e7157a: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff813952e0-ffffffff8139530d: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff813c9da0-ffffffff813c9dcd: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff817d9ef0-ffffffff817d9f1b: find_next_bit (STB_LOCAL)
ffffffff81ebbf89-ffffffff81ebbfbd: find_next_bit.constprop.0 (STB_LOCAL)
ffffffff81ebeb43-ffffffff81ebeb6e: find_next_bit (STB_LOCAL)
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
In arch/x86/events/core.c (ffffffff8100a5e1)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
```
In arch/x86/events/amd/core.c (ffffffff8100c88c)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100f9dc)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff83e663a0)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
```
```
In arch/x86/events/intel/ds.c (ffffffff81019eb3)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
```
```
In arch/x86/events/intel/knc.c (ffffffff8101bc0a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101d500)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff83e69802)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023ac3)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102db9b)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810308ce)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff83e6a3a5)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/xen/enlighten.c (ffffffff81031d4c)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_reboot
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff81032b9f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/suspend.c (ffffffff810333b6)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
```
```
In arch/x86/xen/suspend_hvm.c (ffffffff8103399f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6ed2e)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81038f9c)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp.c (ffffffff810432f9)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff83e71913)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/smp_hvm.c (ffffffff83e71b07)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81045599)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104677f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047697)
Location: include/linux/find.h:49
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048cc5)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
```
```
In arch/x86/kernel/irq.c (ffffffff8104f6d9)
Location: include/linux/find.h:49
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
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
```
```
In arch/x86/kernel/topology.c (ffffffff83e78a16)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105b1aa)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:within_cpu_entry
```
```
In arch/x86/kernel/tsc.c (ffffffff8105d5f6)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
```
```
In arch/x86/kernel/process.c (ffffffff8105ea98)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064285)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810695fa)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106f88f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81070775)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_start
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077198)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81079737)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8107cfb0)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108344b)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81086a7d)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108ab6d)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108b454)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e3fc)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093ba7)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83e85146)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109986a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c47a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff83e8a3b2)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109d2af)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8109fd57)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e5dc)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810a79dd)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e93b71)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a9009)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9985)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b3516)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:hw_break_release_slot
```
```
In arch/x86/kernel/kvm.c (ffffffff83e96535)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/itmt.c (ffffffff810bab19)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
```
```
In arch/x86/kernel/sev.c (ffffffff810bd52a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/init_64.c (ffffffff83e9b9ba)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/tlb.c (ffffffff810c9917)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff83e9c703)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d3942)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:leave_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff83e9e8dd)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In arch/x86/mm/amdtopology.c (ffffffff83e9ec90)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/pti.c (ffffffff83e9f558)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83ea42a2)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff83ea46f6)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810e5f83)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/fork.c:nr_processes
```
```
In kernel/cpu.c (ffffffff83ea5619)
Location: include/linux/find.h:49
Inline: True
Inline callers:
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
```
```
In kernel/softirq.c (ffffffff83ea5a62)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
```
```
In kernel/sysctl.c (ffffffff810f7f3c)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/workqueue.c (ffffffff83ea6438)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/smpboot.c (ffffffff8112998f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/smpboot.c:idle_threads_init
```
```
In kernel/sched/core.c (ffffffff81133e89)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:sched_core_assert_empty
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_unlock
  - kernel/sched/core.c:sched_core_lock
```
```
In kernel/sched/fair.c (ffffffff83ea88c5)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:show_numa_stats
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
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/build_policy.c (ffffffff81164a6b)
Location: include/linux/find.h:49
Inline: True
Inline callers:
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
```
```
In kernel/sched/build_utility.c (ffffffff83ea9178)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:group_init
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
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:cpupri_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:sched_debug_start
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:sd_flags_show
  - kernel/sched/build_utility.c:sugov_stop
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/sched/build_utility.c:__cpuusage_read
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/locking/percpu-rwsem.c (ffffffff820d18c5)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_is_read_locked
```
```
In kernel/power/snapshot.c (ffffffff81187ce8)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
```
```
In kernel/power/energy_model.c (ffffffff8118cf7a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/irqdesc.c (ffffffff811956af)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
```
In kernel/irq/irq_sim.c (ffffffff811a1239)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/proc.c (ffffffff811a242d)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a29b9)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/affinity.c (ffffffff811a6820)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff811a865c)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/update.c (ffffffff811aa4e7)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811ad874)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/rcu/tree.c (ffffffff811b40c6)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
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
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/livepatch/transition.c (ffffffff811bfe69)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module/main.c (ffffffff811cbe60)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/module/main.c:post_relocation
  - kernel/module/main.c:__is_module_percpu_address
```
```
In kernel/profile.c (ffffffff811d225c)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/time/timer.c (ffffffff83eadd48)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/time/timer.c:init_timers
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
```
```
In kernel/time/hrtimer.c (ffffffff811d9f88)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/clocksource.c (ffffffff811e07e4)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/timer_list.c (ffffffff811e2339)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
```
In kernel/time/clockevents.c (ffffffff83eae7ae)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_init_sysfs
```
```
In kernel/time/tick-broadcast.c (ffffffff811eee6f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff811f1a8a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_clock_notify
```
```
In kernel/smp.c (ffffffff811f8eea)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:call_function_init
```
```
In kernel/kexec_file.c (ffffffff81202339)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cgroup.c (ffffffff812101b9)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/cgroup/rstat.c (ffffffff81211079)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:root_cgroup_cputime
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff81216bad)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8121ecd7)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In kernel/stop_machine.c (ffffffff83eb16c3)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
```
```
In kernel/debug/debug_core.c (ffffffff81239bab)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
```
```
In kernel/debug/gdbstub.c (ffffffff8123c7c8)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_get_regs_helper
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81241b06)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8124566f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff812465e5)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/watchdog.c (ffffffff81247895)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
```
```
In kernel/watchdog_hld.c (ffffffff83eb284c)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/relay.c (ffffffff8124c861)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
```
```
In kernel/taskstats.c (ffffffff83eb2b0a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ftrace.c (ffffffff83eb3798)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/ring_buffer.c (ffffffff81262b66)
Location: include/linux/find.h:49
Inline: True
Inline callers:
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
  - kernel/trace/ring_buffer.c:ring_buffer_wake_waiters
```
```
In kernel/trace/trace.c (ffffffff83eb4b55)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:set_buffer_entries
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/pid_list.c (ffffffff81277256)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_next
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127c7a6)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127ecf4)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/trace/fgraph.c (ffffffff812855a4)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff81287386)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128cb63)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
```
```
In kernel/trace/bpf_trace.c (ffffffff83eb68e8)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ac138)
Location: include/linux/find.h:49
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff812b357d)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b8916)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/core.c (ffffffff812c1710)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc
```
```
In kernel/bpf/syscall.c (ffffffff812c5aae)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In kernel/bpf/verifier.c (ffffffff812d5349)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/bpf/task_iter.c (ffffffff83eb8cc1)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_iter_init
```
```
In kernel/bpf/hashtab.c (ffffffff812fba8e)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff812fe390)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/percpu_freelist.c (ffffffff812ff967)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81301293)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/bpf/local_storage.c (ffffffff813031fc)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
```
```
In kernel/bpf/memalloc.c (ffffffff8131c486)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
```
```
In kernel/bpf/devmap.c (ffffffff83eb8ff1)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In kernel/bpf/cpumap.c (ffffffff83eb9095)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff83eb9541)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:perf_output_sample_regs
```
```
In kernel/events/callchain.c (ffffffff8134c3fb)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134e9cf)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_is_used
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81353d4b)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In mm/oom_kill.c (ffffffff813634a2)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/swap.c (ffffffff8136de08)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff83eba5d9)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_del_mm
  - mm/vmscan.c:lru_gen_add_mm
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
```
```
In mm/mmzone.c (ffffffff81392237)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff83eba877)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:all_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/percpu.c (ffffffff83ebb1b7)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/compaction.c (ffffffff83ebd5f8)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/list_lru.c (ffffffff813abff3)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/workingset.c (ffffffff813ad15c)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/mmap_lock.c (ffffffff813b43bf)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/mmap_lock.c:trace_mmap_lock_reg
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/mmap_lock.c:free_memcg_path_bufs
```
```
In mm/rmap.c (ffffffff813d8902)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813dbd84)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/page_alloc.c (ffffffff813efca0)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__zone_set_pageset_high_and_batch
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memory_hotplug.c (ffffffff813f135a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/swapfile.c (ffffffff83ec21c7)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/swap_slots.c (ffffffff814013b8)
Location: include/linux/find.h:49
Inline: True
```
```
In mm/hugetlb.c (ffffffff83ec3a68)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff83ec4985)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff81425415)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:kmem_cache_init
```
```
In mm/memory-tiers.c (ffffffff83ec69af)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
```
```
In mm/khugepaged.c (ffffffff81447e76)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff83ec6fae)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_page_state_local
```
```
In mm/hugetlb_cgroup.c (ffffffff8145c76e)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In mm/memory-failure.c (ffffffff83ec79b5)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_init
```
```
In fs/dcache.c (ffffffff8149fcbf)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
```
```
In fs/inode.c (ffffffff814a2412)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
```
```
In fs/namespace.c (ffffffff814a9df7)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/namespace.c:mnt_get_writers
  - fs/namespace.c:mnt_get_count
```
```
In fs/seq_file.c (ffffffff814b32c1)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hlist_start_percpu
```
```
In fs/buffer.c (ffffffff814d1e6e)
Location: include/linux/find.h:49
Inline: True
```
```
In fs/locks.c (ffffffff83ecaf77)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/locks.c:filelock_init
```
```
In fs/proc/task_mmu.c (ffffffff8152bdfd)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/stat.c (ffffffff8153f1a5)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In fs/proc/uptime.c (ffffffff8153fadc)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In fs/proc/softirqs.c (ffffffff8153fd3b)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
```
```
In fs/proc/kcore.c (ffffffff815451d1)
Location: include/linux/find.h:49
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81596b74)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff815c2106)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/ext4/sysfs.c (ffffffff815cd1f8)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff815f2fcd)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
```
```
In security/selinux/ss/ebitmap.c (ffffffff816824e5)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff816876ef)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff816927a8)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff816970f1)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
```
In security/apparmor/lsm.c (ffffffff83ed3a58)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In security/landlock/fs.c (ffffffff816f277d)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_truncate
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
```
```
In crypto/scompress.c (ffffffff817110c0)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
```
```
In block/bio.c (ffffffff8172e379)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - block/bio.c:bioset_exit
```
```
In block/blk-mq.c (ffffffff83ed8697)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff8174bb31)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
```
In block/blk-stat.c (ffffffff8174c8c5)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/blk-mq-sysfs.c (ffffffff8174d213)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
```
```
In block/blk-mq-cpumap.c (ffffffff8174d94d)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In block/genhd.c (ffffffff81750df3)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_stat_read_all
```
```
In block/blk-cgroup.c (ffffffff81761709)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-iocost.c (ffffffff8176cbcb)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_lat_stat
```
```
In block/blk-mq-pci.c (ffffffff81777764)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
```
```
In block/blk-mq-virtio.c (ffffffff8177787f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
```
```
In block/blk-mq-rdma.c (ffffffff8177794b)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
```
```
In io_uring/io-wq.c (ffffffff817a8087)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:__io_wq_cpu_online
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_cancel_cb
```
```
In lib/random32.c (ffffffff817cccf7)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
```
```
In lib/bitmap.c (ffffffff817ced08)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_find_next_zero_area_off
```
```
In lib/find_bit.c (ffffffff817d7148)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_clump8
```
```
In lib/percpu-refcount.c (ffffffff817d8d9b)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff817ee31c)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
```
```
In lib/percpu_counter.c (ffffffff8188bc31)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_sum_mask
  - lib/percpu_counter.c:percpu_counter_set
```
```
In lib/cpu_rmap.c (ffffffff81891301)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/irq_poll.c (ffffffff83ed99c4)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In lib/sbitmap.c (ffffffff818a34ba)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818b0bde)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b3272)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b599a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b7152)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
```
```
In drivers/gpio/gpiolib.c (ffffffff818bbf45)
Location: include/linux/find.h:49
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (ffffffff818cc4c5)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff818cd0a8)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/search.c (ffffffff818e83ed)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pcie/rcec.c (ffffffff818f7e74)
Location: include/linux/find.h:49
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff818fba65)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819270ff)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/idle/intel_idle.c (ffffffff83edf0b4)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
```
```
In drivers/acpi/processor_core.c (ffffffff8196612f)
Location: include/linux/find.h:49
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff83ee330e)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
```
In drivers/acpi/x86/apple.c (ffffffff81977545)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/processor_thermal.c (ffffffff819d3549)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
```
```
In drivers/acpi/processor_idle.c (ffffffff819d5215)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d65a8)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff819d802a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
```
```
In drivers/acpi/numa/hmat.c (ffffffff819db84a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819df4a7)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_perf_ctrs_in_pcc
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:cppc_allow_fast_switch
  - drivers/acpi/cppc_acpi.c:acpi_cpc_valid
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/pnp/manager.c (ffffffff819eec4b)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_irq
```
```
In drivers/dma/dmaengine.c (ffffffff81a04985)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a9e4)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a174cf)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
```
```
In drivers/xen/grant-table.c (ffffffff81a1807d)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_seq
```
```
In drivers/xen/balloon.c (ffffffff83eea705)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/xen/time.c (ffffffff81a1c799)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/xen/events/events_base.c (ffffffff81a21f6f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
```
In drivers/xen/events/events_2l.c (ffffffff81a22ecf)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a23e3e)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff842b0d2d)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a45925)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/tty/n_tty.c (ffffffff81a4ecd7)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a5f952)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
```
```
In drivers/tty/vt/vt.c (ffffffff81a6d664)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/char/random.c (ffffffff81a94edb)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/hpet.c (ffffffff81a9ae65)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_open
```
```
In drivers/iommu/intel/iommu.c (ffffffff83ef52df)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad7124)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
```
In drivers/iommu/iova.c (ffffffff81ad859a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/iommu/iova.c:alloc_iova_fast
```
```
In drivers/base/cacheinfo.c (ffffffff81af7193)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/power/domain.c (ffffffff81b0c6ce)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_device
```
```
In drivers/base/node.c (ffffffff83ef836f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_read_distance
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b270eb)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2f6af)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/nvdimm/core.c (ffffffff81b4ec2e)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52bd1)
Location: include/linux/find.h:49
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b541a4)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/nvdimm/label.c (ffffffff81b5e983)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff81b8a821)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/spi/spi.c (ffffffff81bd810c)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_alloc_device
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
In drivers/net/loopback.c (ffffffff81bdae4b)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/tun.c (ffffffff81bf030e)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfc30c)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81c04cc4)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_get_stats64
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c592f1)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81c9184f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81c96b80)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/input/input.c (ffffffff81ca732a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (ffffffff81cabd4f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/misc/uinput.c (ffffffff81cb79ae)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccd656)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81cea8d7)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
```
```
In drivers/md/md.c (ffffffff81cf62f5)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
```
```
In drivers/md/dm.c (ffffffff81d0d5fd)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
```
```
In drivers/md/dm-stats.c (ffffffff81d1dd59)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
```
```
In drivers/opp/cpu.c (ffffffff81d2b755)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2e6eb)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d3383d)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d34e42)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:free_policy_dbs_info
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff83f024a2)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d37c13)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:cppc_enable
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d392a9)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81d3bdf4)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff83f0382a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_no_acpi_pss
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d413bd)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
```
In drivers/cpuidle/driver.c (ffffffff81d42a0b)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff83f040ac)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81d6a225)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
```
In drivers/devfreq/governor_passive.c (ffffffff81d82be7)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
```
In drivers/powercap/idle_inject.c (ffffffff81d88091)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
```
In net/core/sock.c (ffffffff81d9a1e9)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
```
```
In net/core/gen_stats.c (ffffffff81db1f20)
Location: include/linux/find.h:49
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff81dba38b)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff83f0ca35)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:dev_change_proto_down_reason
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_get_num_default_rss_queues
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/dst.c (ffffffff81dd4022)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
```
```
In net/core/neighbour.c (ffffffff81dd7576)
Location: include/linux/find.h:49
Inline: True
```
```
In net/core/filter.c (ffffffff81e017a3)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/core/filter.c:bpf_clear_redirect_map
```
```
In net/core/drop_monitor.c (ffffffff83f0d5a6)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
```
In net/core/dst_cache.c (ffffffff81e29fa0)
Location: include/linux/find.h:49
Inline: True
```
```
In net/core/devlink.c (ffffffff81e39c8d)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/core/devlink.c:devl_trap_groups_register
  - net/core/devlink.c:devlink_trap_stats_read
  - net/core/devlink.c:__devlink_reload_stats_update
```
```
In net/core/gro_cells.c (ffffffff81e44e16)
Location: include/linux/find.h:49
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81e5247f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/sch_mq.c (ffffffff81e5385e)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
```
```
In net/sched/sch_api.c (ffffffff81e56156)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/act_api.c (ffffffff81e619cb)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ethtool/ioctl.c (ffffffff81e7995a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
```
```
In net/ipv4/route.c (ffffffff83f0e1be)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/tcp.c (ffffffff81eabb34)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp.c:tcp_orphan_count_sum
```
```
In net/ipv4/tcp_output.c (ffffffff83f0ea8b)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff83f0ebd2)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/icmp.c (ffffffff83f0f405)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/af_inet.c (ffffffff81ef453f)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
```
```
In net/ipv4/fib_semantics.c (ffffffff81effeaa)
Location: include/linux/find.h:49
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81f05617)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:trie_show_usage
```
```
In net/ipv4/proc.c (ffffffff81f19b09)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
```
```
In net/xfrm/xfrm_input.c (ffffffff83f10499)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
```
In net/xfrm/xfrm_proc.c (ffffffff81f4764a)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
```
In net/ipv6/af_inet6.c (ffffffff81f528aa)
Location: include/linux/find.h:49
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f5e4a9)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:snmp6_alloc_dev
```
```
In net/ipv6/route.c (ffffffff83f11395)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7b9ff)
Location: include/linux/find.h:49
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff83f117bb)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_init
```
```
In net/ipv6/proc.c (ffffffff81fb4fbb)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
```
```
In net/ipv6/seg6_local.c (ffffffff81fbbc14)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_counters
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe370)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
```
In net/packet/af_packet.c (ffffffff81fc5d06)
Location: include/linux/find.h:49
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81feb380)
Location: include/linux/find.h:49
Inline: True
```
```
In net/xdp/xsk.c (ffffffff83f12f4d)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init
```
```
In net/mptcp/protocol.c (ffffffff83f13074)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_proto_init
```
```
In net/mptcp/mib.c (ffffffff820062e8)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - net/mptcp/mib.c:mptcp_seq_show
```
```
In lib/cpumask.c (ffffffff8201f865)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_next_wrap
```
```
In lib/vsprintf.c (ffffffff82042915)
Location: include/linux/find.h:49
Inline: True
```
```
In lib/xarray.c (ffffffff8204770c)
Location: include/linux/find.h:49
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
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
In arch/x86/events/core.c (ffffffff81009e31)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
```
```
In arch/x86/events/amd/core.c (ffffffff8100c04c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100efc6)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff83686a10)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
```
```
In arch/x86/events/intel/ds.c (ffffffff81019943)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
```
```
In arch/x86/events/intel/knc.c (ffffffff8101b8db)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101d200)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff8368a192)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff810237e3)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c93b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8368ad35)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/xen/enlighten.c (ffffffff81031d4c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_reboot
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff81032b3f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/suspend.c (ffffffff81033356)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
```
```
In arch/x86/xen/suspend_hvm.c (ffffffff8103392f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368fc4e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81038ecf)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp.c (ffffffff810434f9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff836927f8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/smp_hvm.c (ffffffff83692a47)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_init.c (ffffffff810456d9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
```
```
In arch/x86/hyperv/mmu.c (ffffffff81046a28)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047c27)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048f25)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
```
```
In arch/x86/kernel/irq.c (ffffffff81050389)
Location: include/linux/find.h:54
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
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
```
```
In arch/x86/kernel/nmi.c (ffffffff810536f7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_check
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_snap
```
```
In arch/x86/kernel/topology.c (ffffffff8369afc7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105c6ea)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:within_cpu_entry
```
```
In arch/x86/kernel/tsc.c (ffffffff8105ebf7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
```
```
In arch/x86/kernel/process.c (ffffffff81060188)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065bd1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106ac3a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8107148f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81072375)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_start
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810793b8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107b9e7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8107f35d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810858fb)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108c575)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108dc0d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108e3a7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810912ac)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096b37)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff836a86cf)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
```
In arch/x86/kernel/smp.c (ffffffff8109bade)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109ccea)
Location: include/linux/find.h:54
Inline: True
Inline callers:
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
  - arch/x86/kernel/smpboot.c:topology_update_die_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f5ba)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff836adaa2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a0267)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a2cdb)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b1e7c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810aadad)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b77c0)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810ac229)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810acc6f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b6619)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:hw_break_release_slot
```
```
In arch/x86/kernel/kvm.c (ffffffff836ba0b5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev.c (ffffffff810c0b9a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/init_64.c (ffffffff836bf45a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/tlb.c (ffffffff810ccf93)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff836c0223)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6d22)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:leave_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff836c2a3d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In arch/x86/mm/amdtopology.c (ffffffff836c2e04)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/pti.c (ffffffff836c36e5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff836c8589)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff836c8a76)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810f158b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:nr_processes
```
```
In kernel/cpu.c (ffffffff836c9a40)
Location: include/linux/find.h:54
Inline: True
Inline callers:
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
  - kernel/cpu.c:cpuhp_bringup_mask
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_down_maps_locked
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/softirq.c (ffffffff836ca132)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
```
```
In kernel/sysctl.c (ffffffff811043b2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/workqueue.c (ffffffff836cabf8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/smpboot.c (ffffffff81136e2f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/smpboot.c:idle_threads_init
```
```
In kernel/sched/core.c (ffffffff81142a30)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:sched_core_assert_empty
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_unlock
  - kernel/sched/core.c:sched_core_lock
```
```
In kernel/sched/fair.c (ffffffff836cd311)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:sched_use_asym_prio
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:destroy_cfs_bandwidth
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/build_policy.c (ffffffff8117520b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
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
```
```
In kernel/sched/build_utility.c (ffffffff836cdc59)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:group_init
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
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:cpupri_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:sched_debug_start
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:sd_flags_show
  - kernel/sched/build_utility.c:sugov_stop
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/sched/build_utility.c:__cpuusage_read
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82155c35)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_is_read_locked
```
```
In kernel/power/snapshot.c (ffffffff81198e78)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
```
```
In kernel/power/energy_model.c (ffffffff8119e719)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/irqdesc.c (ffffffff811a707f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
```
In kernel/irq/irq_sim.c (ffffffff811b3049)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/proc.c (ffffffff811b432d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b48b9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/matrix.c (ffffffff811ba32c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/update.c (ffffffff811bc417)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811bf59e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/rcu/tree.c (ffffffff811c8122)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
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
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/livepatch/transition.c (ffffffff811d2949)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module/main.c (ffffffff811df3f0)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/module/main.c:post_relocation
  - kernel/module/main.c:__is_module_percpu_address
```
```
In kernel/profile.c (ffffffff811e6543)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/time/timer.c (ffffffff836d2d88)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/timer.c:init_timers
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
```
```
In kernel/time/hrtimer.c (ffffffff811ee478)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/clocksource.c (ffffffff811f4ce8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/timer_list.c (ffffffff811f6899)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
```
In kernel/time/clockevents.c (ffffffff836d376e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_init_sysfs
```
```
In kernel/time/tick-broadcast.c (ffffffff81203b50)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff8120622d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_clock_notify
```
```
In kernel/smp.c (ffffffff8120db9a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:call_function_init
```
```
In kernel/kexec_file.c (ffffffff81217719)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cgroup.c (ffffffff81225bc9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/cgroup/rstat.c (ffffffff81226a71)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:root_cgroup_cputime
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff8122c49f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff81234dcd)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In kernel/stop_machine.c (ffffffff836d6673)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
```
```
In kernel/debug/debug_core.c (ffffffff81250bbb)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
```
```
In kernel/debug/gdbstub.c (ffffffff81253832)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_get_regs_helper
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81258b86)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8125c6ff)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff8125d655)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/watchdog.c (ffffffff8125ecb5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
```
```
In kernel/watchdog_perf.c (ffffffff836d796c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:hardlockup_detector_perf_restart
  - kernel/watchdog_perf.c:hardlockup_detector_perf_stop
  - kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup
```
```
In kernel/relay.c (ffffffff81263bc8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
```
```
In kernel/taskstats.c (ffffffff836d7c6a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ftrace.c (ffffffff8126a164)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/ring_buffer.c (ffffffff81279b46)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
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
  - kernel/trace/ring_buffer.c:ring_buffer_wake_waiters
```
```
In kernel/trace/trace.c (ffffffff836d9e75)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:set_buffer_entries
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/pid_list.c (ffffffff8128ec5c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_next
```
```
In kernel/trace/trace_hwlat.c (ffffffff812942f6)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/trace/trace_osnoise.c (ffffffff81299a2c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_tracer_stop
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:stop_per_cpu_kthreads
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129b884)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/trace/fgraph.c (ffffffff812a2256)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff812a40c7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a9ae3)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
```
```
In kernel/trace/bpf_trace.c (ffffffff836dbed8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ce7c8)
Location: include/linux/find.h:54
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff812d5e4d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dbf56)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/core.c (ffffffff812e8545)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc
```
```
In kernel/bpf/syscall.c (ffffffff812ecbbe)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In kernel/bpf/verifier.c (ffffffff8130c735)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:mark_precise_scalar_ids
  - kernel/bpf/verifier.c:mark_precise_scalar_ids
```
```
In kernel/bpf/task_iter.c (ffffffff836de1f1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_iter_init
```
```
In kernel/bpf/hashtab.c (ffffffff8132a33e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff8132d044)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8132e4c7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8132fde3)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/bpf/local_storage.c (ffffffff81331c9c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
```
```
In kernel/bpf/memalloc.c (ffffffff8134bf64)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
```
```
In kernel/bpf/devmap.c (ffffffff836de521)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In kernel/bpf/cpumap.c (ffffffff836de5c5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff836deb71)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/core.c:perf_output_sample_regs
```
```
In kernel/events/callchain.c (ffffffff8137d44b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137fb5f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_is_used
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81384f4b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In mm/oom_kill.c (ffffffff813958f2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/swap.c (ffffffff813a0028)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff836dfbe9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_release_memcg
  - mm/vmscan.c:lru_gen_offline_memcg
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_del_mm
  - mm/vmscan.c:lru_gen_add_mm
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
```
```
In mm/mmzone.c (ffffffff813c4c37)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff836dfe87)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:all_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/mm_init.c (ffffffff836e2ff4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:page_alloc_init_late
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:free_area_init_core_hotplug
```
```
In mm/percpu.c (ffffffff836e3809)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/compaction.c (ffffffff836e5aa8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/show_mem.c (ffffffff813de268)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
```
```
In mm/list_lru.c (ffffffff813e0393)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/workingset.c (ffffffff813e154c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/mmap_lock.c (ffffffff813e903f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/mmap_lock.c:trace_mmap_lock_reg
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/mmap_lock.c:free_memcg_path_bufs
```
```
In mm/rmap.c (ffffffff8140ac84)
Location: include/linux/find.h:54
Inline: True
```
```
In mm/vmalloc.c (ffffffff81410624)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
  - mm/vmalloc.c:vmap_ram_vread_iter
  - mm/vmalloc.c:_vm_unmap_aliases
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/page_alloc.c (ffffffff81423820)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__zone_set_pageset_high_and_batch
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
```
```
In mm/memory_hotplug.c (ffffffff81424e9a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/swapfile.c (ffffffff836e77b7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/swap_slots.c (ffffffff81434298)
Location: include/linux/find.h:54
Inline: True
```
```
In mm/hugetlb.c (ffffffff836e8b48)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff836e9aa5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff8145a7c5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:kmem_cache_init
```
```
In mm/memory-tiers.c (ffffffff836eb99f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
```
```
In mm/khugepaged.c (ffffffff8147d826)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff836ebfbe)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_page_state_local
```
```
In mm/hugetlb_cgroup.c (ffffffff814923d9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In mm/memory-failure.c (ffffffff836eca15)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_init
```
```
In fs/exec.c (ffffffff814b886c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/exec.c:mm_init_cid
```
```
In fs/dcache.c (ffffffff814d4fdf)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
```
```
In fs/inode.c (ffffffff814d7642)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
```
```
In fs/namespace.c (ffffffff814df1b7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/namespace.c:mnt_get_writers
  - fs/namespace.c:mnt_get_count
```
```
In fs/seq_file.c (ffffffff814e8311)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hlist_start_percpu
```
```
In fs/buffer.c (ffffffff8150876e)
Location: include/linux/find.h:54
Inline: True
```
```
In fs/locks.c (ffffffff836eff97)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/locks.c:filelock_init
```
```
In fs/proc/task_mmu.c (ffffffff8156416e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/stat.c (ffffffff815774f5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In fs/proc/uptime.c (ffffffff81577e5c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In fs/proc/softirqs.c (ffffffff815780bb)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
```
```
In fs/proc/kcore.c (ffffffff8157cdb1)
Location: include/linux/find.h:54
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff815cd592)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff815f9886)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/ext4/sysfs.c (ffffffff81604b52)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff8162b0bd)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
```
```
In security/selinux/ss/ebitmap.c (ffffffff816ba666)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff816bfa9f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff816cad11)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff816cf600)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
```
In security/apparmor/lsm.c (ffffffff836f88d8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In security/landlock/fs.c (ffffffff8172cbab)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_truncate
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
```
```
In crypto/scompress.c (ffffffff8174bbb0)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
```
```
In block/bio.c (ffffffff8176a649)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/bio.c:bioset_exit
```
```
In block/blk-mq.c (ffffffff836fd9c7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff81788251)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
```
In block/blk-stat.c (ffffffff81789003)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/blk-mq-sysfs.c (ffffffff81789833)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
```
```
In block/blk-mq-cpumap.c (ffffffff81789ecd)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In block/genhd.c (ffffffff8178d3c9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_stat_read_all
```
```
In block/blk-cgroup.c (ffffffff817a0909)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-iocost.c (ffffffff817accde)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_lat_stat
```
```
In block/blk-mq-pci.c (ffffffff817b73e4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
```
```
In block/blk-mq-virtio.c (ffffffff817b74ff)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
```
```
In lib/random32.c (ffffffff8180b107)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
```
```
In lib/bitmap.c (ffffffff8180d1b8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_find_next_zero_area_off
```
```
In lib/find_bit.c (ffffffff81816208)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_clump8
```
```
In lib/percpu-refcount.c (ffffffff81817d7b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8182e71c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
```
```
In lib/percpu_counter.c (ffffffff818ce386)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_set
```
```
In lib/cpu_rmap.c (ffffffff818d3611)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/irq_poll.c (ffffffff836ff464)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In lib/sbitmap.c (ffffffff818e580a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_init_node
```
```
In lib/group_cpus.c (ffffffff818e7250)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818f3bde)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f62c2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f8a4a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fa26f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
```
```
In drivers/gpio/gpiolib.c (ffffffff818fee5d)
Location: include/linux/find.h:54
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8190f535)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81910108)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/search.c (ffffffff8192b9fd)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pcie/rcec.c (ffffffff8193b2d4)
Location: include/linux/find.h:54
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff8193f335)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196b2d1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/idle/intel_idle.c (ffffffff83704b32)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
```
```
In drivers/acpi/processor_core.c (ffffffff819ac6bf)
Location: include/linux/find.h:54
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff83708d1e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
```
In drivers/acpi/x86/apple.c (ffffffff819bdf98)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/processor_thermal.c (ffffffff81a1ab85)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
```
```
In drivers/acpi/processor_idle.c (ffffffff81a1cb55)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1dee8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a1fa37)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
```
```
In drivers/acpi/numa/hmat.c (ffffffff81a234f9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a271b7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_perf_ctrs_in_pcc
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:cppc_allow_fast_switch
  - drivers/acpi/cppc_acpi.c:acpi_cpc_valid
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/pnp/manager.c (ffffffff81a3741b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_irq
```
```
In drivers/dma/dmaengine.c (ffffffff81a4d7e5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a5386b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a6055f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
```
```
In drivers/xen/grant-table.c (ffffffff81a6110d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_seq
```
```
In drivers/xen/balloon.c (ffffffff837100f6)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/xen/time.c (ffffffff81a65959)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/xen/events/events_base.c (ffffffff81a6b306)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
```
In drivers/xen/events/events_2l.c (ffffffff81a6c296)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6d36e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff83af391d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a8fad5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/tty/n_tty.c (ffffffff81a98fd7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aaa012)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
```
```
In drivers/tty/vt/vt.c (ffffffff81ab7cb1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/char/random.c (ffffffff81ae06fb)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/hpet.c (ffffffff81ae66f5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_open
```
```
In drivers/iommu/intel/iommu.c (ffffffff8371af23)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1af76)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b25914)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
```
In drivers/iommu/iova.c (ffffffff81b264da)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/iommu/iova.c:alloc_iova_fast
```
```
In drivers/base/cacheinfo.c (ffffffff81b4545f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/power/domain.c (ffffffff81b5a6e2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_device
```
```
In drivers/base/node.c (ffffffff8371df0f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_read_distance
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b76ea2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/block/xen-blkfront.c (ffffffff81b82af9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/nvdimm/core.c (ffffffff81ba207e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6081)
Location: include/linux/find.h:54
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba76f4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/nvdimm/label.c (ffffffff81bb1f33)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff81bde7b1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/spi/spi.c (ffffffff81c29b62)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_emit_pcpu_stats
```
```
In drivers/net/loopback.c (ffffffff81c318fb)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/tun.c (ffffffff81c4888e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6198c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81c6a3d4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_get_stats64
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc02f1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81cf7f5f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81cfd940)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/input/input.c (ffffffff81d0e50a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (ffffffff81d1332f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/misc/uinput.c (ffffffff81d1f05e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d353eb)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d534e7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
```
```
In drivers/md/md.c (ffffffff81d5dd92)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
```
```
In drivers/md/dm.c (ffffffff81d7651d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
```
```
In drivers/md/dm-stats.c (ffffffff81d86f39)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
```
```
In drivers/opp/cpu.c (ffffffff81d94a09)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9769b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9cbcd)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9e1b2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:free_policy_dbs_info
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff83728392)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81da23fc)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:cppc_enable
  - drivers/cpufreq/amd-pstate.c:pstate_enable
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da3d49)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81da6954)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff837299e0)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81dabd8d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
```
In drivers/cpuidle/driver.c (ffffffff81dacc2b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8372a08c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/firmware/efi/unaccepted_memory.c (ffffffff81dd46ab)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd55e5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
```
In drivers/devfreq/governor_passive.c (ffffffff81df0fc7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
```
In drivers/powercap/idle_inject.c (ffffffff81df6341)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register_full
  - drivers/powercap/idle_inject.c:idle_inject_register_full
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
```
In net/core/sock.c (ffffffff81e08859)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
```
```
In net/core/gen_stats.c (ffffffff81e224f0)
Location: include/linux/find.h:54
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff81e2ac39)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff83732dd5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:dev_change_proto_down_reason
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_get_num_default_rss_queues
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/dst.c (ffffffff81e44da2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
```
```
In net/core/neighbour.c (ffffffff81e4837d)
Location: include/linux/find.h:54
Inline: True
```
```
In net/core/filter.c (ffffffff81e73a73)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/filter.c:bpf_clear_redirect_map
```
```
In net/core/page_pool.c (ffffffff81e82494)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_get_stats
```
```
In net/core/drop_monitor.c (ffffffff83733bb6)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
```
In net/core/dst_cache.c (ffffffff81e9f6c2)
Location: include/linux/find.h:54
Inline: True
```
```
In net/core/gro_cells.c (ffffffff81e9fc16)
Location: include/linux/find.h:54
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81eadcef)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/sch_mq.c (ffffffff81eaf0de)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
```
```
In net/sched/sch_api.c (ffffffff81eb251d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/act_api.c (ffffffff81ebde7b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ethtool/ioctl.c (ffffffff81ed5c5a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
```
```
In net/ipv4/route.c (ffffffff837347ce)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/tcp.c (ffffffff81f0a2f4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp.c:tcp_orphan_count_sum
```
```
In net/ipv4/tcp_output.c (ffffffff8373509b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff837351e2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/icmp.c (ffffffff83735a15)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/af_inet.c (ffffffff81f53e2f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
```
```
In net/ipv4/fib_semantics.c (ffffffff81f5f92a)
Location: include/linux/find.h:54
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81f65067)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:trie_show_usage
```
```
In net/ipv4/proc.c (ffffffff81f7a1e9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
```
```
In net/xfrm/xfrm_input.c (ffffffff83736ac9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
```
In net/xfrm/xfrm_proc.c (ffffffff81fa7120)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
```
In net/ipv6/af_inet6.c (ffffffff81fb22aa)
Location: include/linux/find.h:54
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fbe1a9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:snmp6_alloc_dev
```
```
In net/ipv6/route.c (ffffffff837379e5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdbc12)
Location: include/linux/find.h:54
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff83737e0b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_init
```
```
In net/ipv6/proc.c (ffffffff82015707)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
```
```
In net/ipv6/seg6_local.c (ffffffff8201c514)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_counters
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f1d0)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
```
In net/packet/af_packet.c (ffffffff82026386)
Location: include/linux/find.h:54
Inline: True
```
```
In net/devlink/leftover.c (ffffffff8203c695)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_trap_groups_register
  - net/devlink/leftover.c:devlink_trap_stats_read
```
```
In net/devlink/dev.c (ffffffff820444a9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/devlink/dev.c:__devlink_reload_stats_update
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82067628)
Location: include/linux/find.h:54
Inline: True
```
```
In net/xdp/xsk.c (ffffffff837395fd)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init
```
```
In net/mptcp/protocol.c (ffffffff83739724)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_proto_init
```
```
In net/mptcp/mib.c (ffffffff82082677)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/mptcp/mib.c:mptcp_seq_show
```
```
In lib/cpumask.c (ffffffff8209f875)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_next_wrap
```
```
In lib/vsprintf.c (ffffffff820c0e7b)
Location: include/linux/find.h:54
Inline: True
```
```
In lib/xarray.c (ffffffff820c5da2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
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
In arch/x86/events/core.c (ffffffff8100f551)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
```
```
In arch/x86/events/amd/core.c (ffffffff81011830)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff81014706)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff838b5c20)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
```
```
In arch/x86/events/intel/ds.c (ffffffff8101f4a3)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
```
```
In arch/x86/events/intel/knc.c (ffffffff8102145b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/lbr.c (ffffffff81023190)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff838b9d52)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81029912)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81032a98)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff838ba8f5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/xen/enlighten.c (ffffffff8103803c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_reboot
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/time.c (ffffffff81038e2f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_timer_resume
```
```
In arch/x86/xen/suspend.c (ffffffff81039666)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
```
```
In arch/x86/xen/suspend_hvm.c (ffffffff81039c2f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bf79e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f37f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp.c (ffffffff810499f9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff838c2346)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/smp_hvm.c (ffffffff838c25b7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104bda9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104d238)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e390)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81050195)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
```
```
In arch/x86/kernel/irq.c (ffffffff810575b9)
Location: include/linux/find.h:54
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
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
```
```
In arch/x86/kernel/nmi.c (ffffffff8105a917)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_check
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_snap
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff810637aa)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:within_cpu_entry
```
```
In arch/x86/kernel/tsc.c (ffffffff81065ca7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
```
```
In arch/x86/kernel/process.c (ffffffff81067208)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106d038)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8107203a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078c4f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81079b95)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_start
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080c38)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81086e6c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c8dd)
Location: include/linux/find.h:54
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81092855)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81094f9d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81095737)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098690)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e0a7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff838d8c5b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
```
In arch/x86/kernel/cpu/debugfs.c (ffffffff838d98f2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/debugfs.c:cpu_init_debugfs
```
```
In arch/x86/kernel/smp.c (ffffffff810a3055)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a422a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
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
  - arch/x86/kernel/smpboot.c:topology_update_die_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6a4a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff838de082)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a7889)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a9b30)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e1cb7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810b1d7d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e8108)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2fc8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b385f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kgdb.c (ffffffff810bda59)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:hw_break_release_slot
```
```
In arch/x86/kernel/kvm.c (ffffffff838eaa00)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev.c (ffffffff810c7ffa)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/init_64.c (ffffffff838efefa)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/tlb.c (ffffffff810d5663)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff838f0d43)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df552)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:leave_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff838f345d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In arch/x86/mm/amdtopology.c (ffffffff838f39f4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/pti.c (ffffffff838f4385)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff838f9189)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff838f96a5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810fa96d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:nr_processes
```
```
In kernel/cpu.c (ffffffff838fa6b0)
Location: include/linux/find.h:54
Inline: True
Inline callers:
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
  - kernel/cpu.c:cpuhp_bringup_mask
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/softirq.c (ffffffff838fade2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
```
```
In kernel/sysctl.c (ffffffff8110dd02)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/workqueue.c (ffffffff838fbba8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/workqueue.c:init_pod_type
  - kernel/workqueue.c:init_pod_type
  - kernel/workqueue.c:init_pod_type
  - kernel/workqueue.c:wq_affn_dfl_set
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init_topology
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/smpboot.c (ffffffff8114200f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/smpboot.c:idle_threads_init
```
```
In kernel/sched/core.c (ffffffff8114e24f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:cpu_local_stat_show
  - kernel/sched/core.c:cpu_cfs_local_stat_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:sched_core_assert_empty
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_unlock
  - kernel/sched/core.c:sched_core_lock
```
```
In kernel/sched/fair.c (ffffffff838fe71f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:should_we_balance
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:sched_use_asym_prio
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:destroy_cfs_bandwidth
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/build_policy.c (ffffffff8118351c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
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
```
```
In kernel/sched/build_utility.c (ffffffff838ff09e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_sched_groups_capacity
  - kernel/sched/build_utility.c:init_sched_groups_capacity
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sched_is_eas_possible
  - kernel/sched/build_utility.c:sched_is_eas_possible
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:cpupri_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:sd_flags_show
  - kernel/sched/build_utility.c:sugov_stop
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/sched/build_utility.c:__cpuusage_read
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82238a75)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_is_read_locked
```
```
In kernel/power/snapshot.c (ffffffff811a7e04)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
```
```
In kernel/power/energy_model.c (ffffffff811ad8d9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/irqdesc.c (ffffffff811b6bdf)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
```
In kernel/irq/irq_sim.c (ffffffff811c2e69)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/proc.c (ffffffff811c41ad)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c4739)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/matrix.c (ffffffff811ca1ec)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
```
In kernel/rcu/update.c (ffffffff811cc8a7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811cfa0e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/rcu/tree.c (ffffffff83903ae6)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
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
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_organize_nocb_kthreads
```
```
In kernel/livepatch/transition.c (ffffffff811e75c9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module/main.c (ffffffff811f5120)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/module/main.c:post_relocation
  - kernel/module/main.c:__is_module_percpu_address
```
```
In kernel/profile.c (ffffffff811fc293)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/time/timer.c (ffffffff83904b48)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/timer.c:init_timers
  - kernel/time/timer.c:next_expiry_recalc
  - kernel/time/timer.c:next_expiry_recalc
```
```
In kernel/time/hrtimer.c (ffffffff812045f8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/clocksource.c (ffffffff8120ae3f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/timer_list.c (ffffffff8120ca39)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
```
In kernel/time/clockevents.c (ffffffff8390552e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_init_sysfs
```
```
In kernel/time/tick-broadcast.c (ffffffff8121a110)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff8121d43d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In kernel/smp.c (ffffffff8122532a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:call_function_init
```
```
In kernel/crash_core.c (ffffffff8122a605)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cgroup.c (ffffffff8123d859)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/cgroup/rstat.c (ffffffff8123e6f2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:root_cgroup_cputime
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff8124452e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e9ed)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In kernel/stop_machine.c (ffffffff83908ab3)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init
```
```
In kernel/debug/debug_core.c (ffffffff8126aa0b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
```
```
In kernel/debug/gdbstub.c (ffffffff8126d6a2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_get_regs_helper
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81272a76)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8127663f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff81277595)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/watchdog.c (ffffffff81278cc5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
```
```
In kernel/watchdog_perf.c (ffffffff83909e7c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:hardlockup_detector_perf_restart
  - kernel/watchdog_perf.c:hardlockup_detector_perf_stop
  - kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup
```
```
In kernel/relay.c (ffffffff8127d9b8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
```
```
In kernel/taskstats.c (ffffffff8390a17a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ftrace.c (ffffffff812842d4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/ring_buffer.c (ffffffff81294626)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
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
  - kernel/trace/ring_buffer.c:ring_buffer_wake_waiters
```
```
In kernel/trace/trace.c (ffffffff8390c3d5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:set_buffer_entries
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
```
```
In kernel/trace/pid_list.c (ffffffff812aa12c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_next
```
```
In kernel/trace/trace_hwlat.c (ffffffff812af956)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b50ac)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_tracer_stop
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:stop_per_cpu_kthreads
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b6f63)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/trace/fgraph.c (ffffffff812bd9e7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff812bfa27)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c57f3)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
```
```
In kernel/trace/bpf_trace.c (ffffffff8390e508)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec1c8)
Location: include/linux/find.h:54
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff812f395d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fa036)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/core.c (ffffffff813068b5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc
```
```
In kernel/bpf/syscall.c (ffffffff8130b36e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In kernel/bpf/verifier.c (ffffffff81328a36)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:mark_precise_scalar_ids
  - kernel/bpf/verifier.c:mark_precise_scalar_ids
```
```
In kernel/bpf/map_iter.c (ffffffff813483aa)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/map_iter.c:bpf_map_sum_elem_count
```
```
In kernel/bpf/task_iter.c (ffffffff83910831)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_iter_init
```
```
In kernel/bpf/hashtab.c (ffffffff8134d1de)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff813513a4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/percpu_freelist.c (ffffffff813529e7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81354303)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/bpf/local_storage.c (ffffffff8135623c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
```
```
In kernel/bpf/memalloc.c (ffffffff813733d1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:check_leaked_objs
  - kernel/bpf/memalloc.c:check_leaked_objs
  - kernel/bpf/memalloc.c:bpf_mem_alloc_percpu_unit_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
```
```
In kernel/bpf/devmap.c (ffffffff83910b61)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In kernel/bpf/cpumap.c (ffffffff83910c05)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff839111b1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/core.c:perf_output_sample_regs
```
```
In kernel/events/callchain.c (ffffffff813a66ab)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a8d6f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_is_used
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff813ae2ba)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In mm/oom_kill.c (ffffffff813bf6b2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/swap.c (ffffffff813c9ca8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff83912469)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_release_memcg
  - mm/vmscan.c:lru_gen_offline_memcg
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_del_mm
  - mm/vmscan.c:lru_gen_add_mm
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/shrinker.c (ffffffff813e4991)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/shrinker.c:shrink_slab_memcg
  - mm/shrinker.c:reparent_shrinker_deferred
  - mm/shrinker.c:expand_one_shrinker_info
  - mm/shrinker.c:alloc_shrinker_info
  - mm/shrinker.c:free_shrinker_info
```
```
In mm/mmzone.c (ffffffff813ef657)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff83912737)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:all_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/mm_init.c (ffffffff83915884)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:page_alloc_init_late
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:free_area_init_core_hotplug
```
```
In mm/percpu.c (ffffffff83916099)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_alloc_size
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/compaction.c (ffffffff839182d8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/show_mem.c (ffffffff81408058)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
```
```
In mm/list_lru.c (ffffffff8140a6f3)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/mmap_lock.c (ffffffff81413cc1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/mmap_lock.c:trace_mmap_lock_reg
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/mmap_lock.c:free_memcg_path_bufs
```
```
In mm/rmap.c (ffffffff8143a4d0)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143cf84)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
  - mm/vmalloc.c:vmap_ram_vread_iter
  - mm/vmalloc.c:_vm_unmap_aliases
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/page_alloc.c (ffffffff81450760)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_pcp_cacheinfo
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__zone_set_pageset_high_and_batch
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
```
```
In mm/memory_hotplug.c (ffffffff814520da)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/slub.c (ffffffff81455895)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:kmem_cache_init
```
```
In mm/swapfile.c (ffffffff8391a847)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/swap_slots.c (ffffffff8146d698)
Location: include/linux/find.h:54
Inline: True
```
```
In mm/zswap.c (ffffffff8146f1fc)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/zswap.c:shrink_memcg
```
```
In mm/hugetlb.c (ffffffff8391c0d8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:remove_pool_hugetlb_folio
  - mm/hugetlb.c:alloc_pool_huge_folio
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8391ce65)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:interleave_nid
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/memory-tiers.c (ffffffff8391e5d0)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
```
```
In mm/khugepaged.c (ffffffff814abbf6)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff8391ef7e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In mm/hugetlb_cgroup.c (ffffffff814c1de9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In mm/memory-failure.c (ffffffff8391fa15)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_init
```
```
In fs/exec.c (ffffffff814ead7c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/exec.c:mm_init_cid
```
```
In fs/dcache.c (ffffffff815073df)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
```
```
In fs/inode.c (ffffffff81509952)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
```
```
In fs/namespace.c (ffffffff81511fa7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/namespace.c:mnt_get_writers
  - fs/namespace.c:mnt_get_count
```
```
In fs/seq_file.c (ffffffff8151c1a1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hlist_start_percpu
```
```
In fs/buffer.c (ffffffff8153d61e)
Location: include/linux/find.h:54
Inline: True
```
```
In fs/locks.c (ffffffff83922fa7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/locks.c:filelock_init
```
```
In fs/proc/task_mmu.c (ffffffff8159afe2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/stat.c (ffffffff815afdfe)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In fs/proc/uptime.c (ffffffff815b05be)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In fs/proc/softirqs.c (ffffffff815b07eb)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
```
```
In fs/proc/kcore.c (ffffffff815b56d1)
Location: include/linux/find.h:54
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81605e12)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff81632486)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/sysfs.c (ffffffff8163d812)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff8166448d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
```
```
In security/selinux/ss/ebitmap.c (ffffffff816f70f6)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff816fc2e1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81707950)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8170bc20)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
```
In security/apparmor/lsm.c (ffffffff8392bec0)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In security/landlock/ruleset.c (ffffffff8176c28d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_init_layer_masks
  - security/landlock/ruleset.c:landlock_unmask_layers
```
```
In security/landlock/fs.c (ffffffff8176d723)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:is_eacces
```
```
In crypto/scompress.c (ffffffff8178da90)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
```
```
In block/bio.c (ffffffff817acaa9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/bio.c:bioset_exit
```
```
In block/blk-mq.c (ffffffff83931026)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
```
In block/blk-mq-tag.c (ffffffff817ca921)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
```
In block/blk-stat.c (ffffffff817cb763)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/blk-mq-sysfs.c (ffffffff817cbfcd)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
```
```
In block/blk-mq-cpumap.c (ffffffff817cc64d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In block/genhd.c (ffffffff817cfc29)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_stat_read_all
```
```
In block/blk-cgroup.c (ffffffff817e4468)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-iocost.c (ffffffff817f0add)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_lat_stat
```
```
In block/blk-mq-pci.c (ffffffff817fbdf4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
```
```
In block/blk-mq-virtio.c (ffffffff817fbf0f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
```
```
In lib/random32.c (ffffffff818518e7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
```
```
In lib/bitmap.c (ffffffff81852e68)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_find_next_zero_area_off
```
```
In lib/find_bit.c (ffffffff8185b348)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_clump8
```
```
In lib/percpu-refcount.c (ffffffff8185d07b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/bitmap-str.c (ffffffff8186171b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/bitmap-str.c:bitmap_parse
```
```
In lib/genalloc.c (ffffffff818802dc)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_best_fit
```
```
In lib/percpu_counter.c (ffffffff8191fda6)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_set
```
```
In lib/cpu_rmap.c (ffffffff819256f1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/irq_poll.c (ffffffff83932cb4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In lib/sbitmap.c (ffffffff8192c80a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_init_node
```
```
In lib/group_cpus.c (ffffffff8192e26b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8193b40e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193d0ac)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff819403da)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81941643)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
```
```
In drivers/gpio/gpiolib.c (ffffffff8194675d)
Location: include/linux/find.h:54
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (ffffffff81957335)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81957fd8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/search.c (ffffffff8197434d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pcie/rcec.c (ffffffff81984164)
Location: include/linux/find.h:54
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff819880d5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff819b17a2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b47dd)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/idle/intel_idle.c (ffffffff83938042)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
```
```
In drivers/acpi/processor_core.c (ffffffff819f697c)
Location: include/linux/find.h:54
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff8393c0ee)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
```
In drivers/acpi/x86/apple.c (ffffffff81a08865)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/processor_thermal.c (ffffffff81a65e85)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
```
```
In drivers/acpi/processor_idle.c (ffffffff81a67e35)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a691f8)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a6ad57)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
```
```
In drivers/acpi/numa/hmat.c (ffffffff8393f6d4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:__hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a72327)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_perf_ctrs_in_pcc
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:cppc_allow_fast_switch
  - drivers/acpi/cppc_acpi.c:acpi_cpc_valid
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/pnp/manager.c (ffffffff81a82bdb)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_irq
```
```
In drivers/dma/dmaengine.c (ffffffff81a99485)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f61b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
```
```
In drivers/pmdomain/core.c (ffffffff81aa2142)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_add_device
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81ab2d9f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
```
```
In drivers/xen/grant-table.c (ffffffff81ab393d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_seq
```
```
In drivers/xen/balloon.c (ffffffff83943a6b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/xen/time.c (ffffffff81ab81b9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/xen/events/events_base.c (ffffffff81abd3d6)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
```
In drivers/xen/events/events_2l.c (ffffffff81abe356)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abf3de)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff83d4f67d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/regulator/irq_helpers.c (ffffffff81ae2345)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/tty/n_tty.c (ffffffff81aeb677)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
```
In drivers/tty/vt/keyboard.c (ffffffff81afcad2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
```
```
In drivers/tty/vt/vt.c (ffffffff81b0a9b1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/char/random.c (ffffffff81b33afb)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/hpet.c (ffffffff81b39a85)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_open
```
```
In drivers/iommu/intel/iommu.c (ffffffff8394ea03)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e862)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:alloc_irte
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b70aa6)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7c6a2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
```
In drivers/iommu/iova.c (ffffffff81b7d302)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/iommu/iova.c:alloc_iova_fast
```
```
In drivers/base/cpu.c (ffffffff83950d2e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_dev_init
```
```
In drivers/base/cacheinfo.c (ffffffff81b9dc3a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:update_per_cpu_data_slice_size
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/node.c (ffffffff839518df)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_read_distance
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcac72)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd69e9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/nvdimm/core.c (ffffffff81bf620e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa301)
Location: include/linux/find.h:54
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfb9a4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/nvdimm/label.c (ffffffff81c06423)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff81c3368a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/gpu/drm/drm_print.c (ffffffff81cad4b1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_print.c:drm_print_bits
```
```
In drivers/spi/spi.c (ffffffff81cdc3b2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_emit_pcpu_stats
```
```
In drivers/net/loopback.c (ffffffff81ce476b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/tun.c (ffffffff81cfe1ee)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1837c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81d1edb4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_get_stats64
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d750b1)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81dad88f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81db32a0)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/input/input.c (ffffffff81dc415a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (ffffffff81dc8f5f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/misc/uinput.c (ffffffff81dd4d8e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb57b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a227)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
```
```
In drivers/md/md.c (ffffffff81e14ce2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
```
```
In drivers/md/dm.c (ffffffff81e2d74d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
```
```
In drivers/md/dm-stats.c (ffffffff81e3e649)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
```
```
In drivers/opp/cpu.c (ffffffff81e4c519)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4f31b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e5488d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e55f42)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:free_policy_dbs_info
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8395c322)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81e5a30c)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:cppc_enable
  - drivers/cpufreq/amd-pstate.c:pstate_enable
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5bdd9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81e5e9e4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8395d995)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81e63e2d)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
```
In drivers/cpuidle/driver.c (ffffffff81e64ccb)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8395e03b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/firmware/efi/unaccepted_memory.c (ffffffff81e8c775)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d735)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
```
In drivers/devfreq/governor_passive.c (ffffffff81ea75e7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
```
In drivers/powercap/idle_inject.c (ffffffff81eaca31)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register_full
  - drivers/powercap/idle_inject.c:idle_inject_register_full
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
```
In net/core/sock.c (ffffffff81ec52c9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
```
```
In net/core/gen_stats.c (ffffffff81ee0430)
Location: include/linux/find.h:54
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff81ee8a49)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff839672b5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_proto_down_reason
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_get_num_default_rss_queues
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/dst.c (ffffffff81f03a22)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
```
```
In net/core/neighbour.c (ffffffff81f06f33)
Location: include/linux/find.h:54
Inline: True
```
```
In net/core/filter.c (ffffffff81f33233)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/filter.c:bpf_clear_redirect_map
```
```
In net/core/page_pool.c (ffffffff81f434e4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_get_stats
```
```
In net/core/drop_monitor.c (ffffffff839680f6)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
```
In net/core/dst_cache.c (ffffffff81f61e32)
Location: include/linux/find.h:54
Inline: True
```
```
In net/core/gro_cells.c (ffffffff81f62376)
Location: include/linux/find.h:54
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81f7077f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/sch_mq.c (ffffffff81f71b7b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
```
```
In net/sched/sch_api.c (ffffffff81f74fcd)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/act_api.c (ffffffff81f8108b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ethtool/ioctl.c (ffffffff81f9934a)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
```
```
In net/ipv4/route.c (ffffffff83968d7e)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/tcp.c (ffffffff81fd3a84)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_orphan_count_sum
```
```
In net/ipv4/tcp_output.c (ffffffff8396965b)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff839697a2)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/icmp.c (ffffffff8396a085)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/af_inet.c (ffffffff8201a1ef)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
```
```
In net/ipv4/fib_semantics.c (ffffffff82025efa)
Location: include/linux/find.h:54
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff8202b637)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:trie_show_usage
```
```
In net/ipv4/proc.c (ffffffff820408de)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204d397)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:cpool_cleanup_work_cb
  - net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch
```
```
In net/xfrm/xfrm_input.c (ffffffff8396b139)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
```
In net/xfrm/xfrm_proc.c (ffffffff820743d0)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
```
In net/ipv6/af_inet6.c (ffffffff8207f9fe)
Location: include/linux/find.h:54
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8208b5f9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:snmp6_alloc_dev
```
```
In net/ipv6/route.c (ffffffff8396c09f)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
```
```
In net/ipv6/ip6_fib.c (ffffffff820a9742)
Location: include/linux/find.h:54
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8396c4bb)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_init
```
```
In net/ipv6/proc.c (ffffffff820e4847)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
```
```
In net/ipv6/seg6_local.c (ffffffff820eb4e4)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_counters
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee300)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
```
In net/packet/af_packet.c (ffffffff820f5d96)
Location: include/linux/find.h:54
Inline: True
```
```
In net/devlink/dev.c (ffffffff821033a9)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/devlink/dev.c:__devlink_reload_stats_update
```
```
In net/devlink/trap.c (ffffffff82115b15)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/devlink/trap.c:devl_trap_groups_register
  - net/devlink/trap.c:devlink_trap_stats_read
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213a8aa)
Location: include/linux/find.h:54
Inline: True
```
```
In net/xdp/xsk.c (ffffffff8396dddd)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init
```
```
In net/mptcp/protocol.c (ffffffff8396df09)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_proto_init
```
```
In net/mptcp/mib.c (ffffffff82157ce7)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - net/mptcp/mib.c:mptcp_seq_show
```
```
In lib/cpumask.c (ffffffff821778d5)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_next_wrap
```
```
In lib/vsprintf.c (ffffffff8219b7ab)
Location: include/linux/find.h:54
Inline: True
```
```
In lib/xarray.c (ffffffff821a0722)
Location: include/linux/find.h:54
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffff8000106337c8)
Location: lib/find_bit.c:67
Inline: False
Direct callers:
  - arch/arm64/kernel/fpsimd.c:find_supported_vector_length
  - arch/arm64/kernel/setup.c:topology_init
  - arch/arm64/kernel/setup.c:topology_init
  - arch/arm64/kernel/cpufeature.c:cpu_enable_non_boot_scope_capabilities
  - arch/arm64/kernel/cpufeature.c:cpu_enable_non_boot_scope_capabilities
  - arch/arm64/mm/numa.c:numa_init
  - arch/arm64/mm/numa.c:numa_init
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
  - arch/arm64/kvm/pmu.c:kvm_vcpu_pmu_disable_el0
  - arch/arm64/kvm/pmu.c:kvm_vcpu_pmu_disable_el0
  - arch/arm64/kvm/pmu.c:kvm_vcpu_pmu_enable_el0
  - arch/arm64/kvm/pmu.c:kvm_vcpu_pmu_enable_el0
  - virt/kvm/arm/vgic/vgic-mmio.c:__vgic_mmio_write_sactive
  - virt/kvm/arm/vgic/vgic-mmio.c:__vgic_mmio_write_sactive
  - virt/kvm/arm/vgic/vgic-mmio.c:__vgic_mmio_write_cactive
  - virt/kvm/arm/vgic/vgic-mmio.c:__vgic_mmio_write_cactive
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cpending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cpending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_spending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_spending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cenable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cenable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_senable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_senable
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:next_online_pgdat
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:s_show
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
  - mm/slub.c:list_locations
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-gic.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_handle_cascade_irq
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_handle_cascade_irq
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_handle_cascade_irq
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_handle_cascade_irq
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_irq_handler
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_irq_handler
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_irq_handler
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_set_affinity
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_compose_msg
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_release_resources
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_handler
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_handler
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_handle_bank
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_handle_bank
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_handler
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_handler
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_handler
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_handle_msi_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_handle_msi_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_leg_handler
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_set_affinity
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_set_affinity
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_clk_setup
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_clk_setup
  - drivers/clk/sunxi/clk-sun6i-apb0-gates.c:sun6i_a31_apb0_gates_clk_probe
  - drivers/clk/sunxi/clk-sun6i-apb0-gates.c:sun6i_a31_apb0_gates_clk_probe
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
  - drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done
  - drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/iommu/arm-smmu.c:arm_smmu_device_shutdown
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/edac/altera_edac.c:altr_edac_a10_irq_handler
  - drivers/edac/altera_edac.c:altr_edac_a10_irq_handler
  - drivers/edac/altera_edac.c:altr_edac_a10_irq_handler
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_register_em
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen2_general
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen2_general
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_isr
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_isr
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_isr
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_isr
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_isr
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_isr
  - drivers/perf/qcom_l2_pmu.c:l2_cache_handle_irq
  - drivers/perf/qcom_l2_pmu.c:l2_cache_handle_irq
  - drivers/perf/qcom_l2_pmu.c:l2_cache_handle_irq
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_online_cpu
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__event_init
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__handle_irq
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__handle_irq
  - drivers/perf/xgene_pmu.c:xgene_perf_event_init
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/idr.c:ida_free
  - lib/nodemask.c:__next_node_in
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffff8000106337c8-ffff80001063383c: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (c0000000007d8b60)
Location: lib/find_bit.c:67
Inline: False
Direct callers:
  - arch/powerpc/kernel/irq.c:irq_choose_cpu
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_offline
  - arch/powerpc/kernel/setup-common.c:c_start
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan_init
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan
  - arch/powerpc/kernel/iommu.c:iommu_take_ownership
  - arch/powerpc/kernel/iommu.c:iommu_tce_table_put
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
  - arch/powerpc/mm/numa.c:find_and_online_cpu_nid
  - arch/powerpc/mm/numa.c:find_and_online_cpu_nid
  - arch/powerpc/mm/numa.c:hot_add_scn_to_nid
  - arch/powerpc/mm/numa.c:hot_add_scn_to_nid
  - arch/powerpc/mm/numa.c:initmem_init
  - arch/powerpc/mm/numa.c:initmem_init
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/mm/numa.c:numa_setup_cpu
  - arch/powerpc/mm/numa.c:dump_numa_cpu_topology
  - arch/powerpc/mm/numa.c:dump_numa_cpu_topology
  - arch/powerpc/mm/slice.c:slice_get_unmapped_area
  - arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target
  - arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask
  - arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask
  - arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_cpu_disable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_bus_PE
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_bus_PE
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_cpu_disable
  - arch/powerpc/xmon/xmon.c:cpus_are_in_xmon
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_check_resend
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_check_resend
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:next_online_pgdat
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:s_show
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_bind
  - mm/mempolicy.c:mpol_new_interleave
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:new_node_page
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_destroy
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_register_em
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/idr.c:ida_free
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
```
**Symbols:**

```
c0000000007d8b60-c0000000007d8be4: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffe0004617f0)
Location: lib/find_bit.c:67
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:input_reset_device
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/opp/of.c:dev_pm_opp_of_register_em
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/idr.c:ida_free
  - lib/nodemask.c:__next_node_in
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffe0004617f0-ffffffe000461880: find_next_bit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815214a0)
Location: lib/find_bit.c:67
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/events/core.c:perf_output_sample_regs
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:s_show
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_mpath_clear_current_path
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff815214a0-ffffffff815214fb: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81511790)
Location: lib/find_bit.c:67
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/events/core.c:perf_output_sample_regs
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:s_show
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_add_dimm
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_mpath_clear_current_path
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/hv/vmbus_drv.c:vmbus_isr
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81511790-ffffffff815117eb: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8151d530)
Location: lib/find_bit.c:67
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/events/core.c:perf_output_sample_regs
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:s_show
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff8151d530-ffffffff8151d58b: find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int find_next_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81536da0)
Location: lib/find_bit.c:67
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/events/core.c:perf_output_sample_regs
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:next_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:s_show
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/kcore.c:kcore_update_ram
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81536da0-ffffffff81536dfb: find_next_bit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
