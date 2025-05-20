# Function: <code>find_first_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff813fdea0)
Location: lib/find_bit.c:82
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/rapl.c:rapl_cpu_notifier
  - arch/x86/events/intel/rapl.c:rapl_cpu_notifier
  - arch/x86/events/intel/rapl.c:rapl_cpu_notifier
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_set_distance
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:init_workqueues
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
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
  - kernel/cpuset.c:update_domain_attr_tree
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:cpuset_write_s64
  - kernel/cpuset.c:cpuset_spread_node
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_index_to_cpu
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd
  - mm/mmzone.c:first_online_pgdat
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:list_lru_destroy
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:next_node_allowed
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:policy_zonelist
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_parse_str
  - mm/slub.c:list_locations
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - fs/dcache.c:shrink_dcache_sb
  - fs/buffer.c:free_more_memory
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/kcore.c:kcore_update_ram
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq-tag.c:bt_tags_for_each
  - block/blk-mq-tag.c:bt_for_each
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_remap
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/gpio/gpio-zx.c:zx_irq_handler
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/sysrq.c:moom_callback
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/node.c:node_read_distance
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_register_device
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/cpufreq/cpufreq.c:cpufreq_frequency_get_table
  - drivers/cpufreq/cpufreq.c:first_policy
  - drivers/cpufreq/cpufreq.c:first_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline_finish
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare
  - drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare
  - drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - arch/x86/power/cpu.c:bsp_pm_callback
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff813fdea0-ffffffff813fdef3: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81445510)
Location: lib/find_bit.c:82
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:numa_set_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/affinity.c:irq_create_affinity_mask
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_s64
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:update_domain_attr_tree
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_index_to_cpu
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:early_pfn_to_nid
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:first_online_pgdat
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:list_lru_destroy
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:policy_zonelist
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
  - mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf
  - mm/slub.c:list_locations
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - fs/dcache.c:shrink_dcache_sb
  - fs/buffer.c:free_more_memory
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/kcore.c:kcore_update_ram
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq-tag.c:bt_tags_for_each
  - block/blk-mq-tag.c:bt_for_each
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - lib/nodemask.c:__next_node_in
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/gpio/gpio-zx.c:zx_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:rand_initialize
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/node.c:node_read_distance
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - arch/x86/power/cpu.c:bsp_pm_callback
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
```
**Symbols:**

```
ffffffff81445510-ffffffff8144555c: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81463d00)
Location: lib/find_bit.c:82
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_s64
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:update_domain_attr_tree
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:early_pfn_to_nid
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:setup_vmstat
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:list_lru_destroy
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
  - mm/mempolicy.c:mpol_new_bind
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_preferred
  - mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:new_node_page
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - fs/dcache.c:shrink_dcache_sb
  - fs/buffer.c:free_more_memory
  - fs/proc/kcore.c:kcore_update_ram
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq-cpumap.c:get_first_sibling
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:rand_initialize
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - arch/x86/power/cpu.c:bsp_pm_callback
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
```
**Symbols:**

```
ffffffff81463d00-ffffffff81463d4c: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81468da0)
Location: lib/find_bit.c:82
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domain
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:early_pfn_to_nid
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/frontswap.c:frontswap_register_ops
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_interleave
  - mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_create
  - mm/memory_hotplug.c:new_node_page
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
  - fs/buffer.c:free_more_memory
  - fs/proc/kcore.c:kcore_update_ram
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_next_cpu
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:rand_initialize
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - lib/idr.c:ida_remove
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff81468da0-ffffffff81468dec: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81495060)
Location: lib/find_bit.c:82
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:select_task_rq_fair
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
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/isolation.c:bitmap_empty
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/devmap.c:__dev_map_flush
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/memremap.c:order_at
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:early_pfn_to_nid
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_interleave
  - mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_create
  - mm/memory_hotplug.c:new_node_page
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
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_next_cpu
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:rand_initialize
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
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
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - lib/idr.c:ida_remove
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff81495060-ffffffff814950ad: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814ca410)
Location: lib/find_bit.c:102
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:select_task_rq_fair
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
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/isolation.c:bitmap_empty
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/devmap.c:__dev_map_flush
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/memremap.c:order_at
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:early_pfn_to_nid
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_interleave
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:new_node_page
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
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
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
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - lib/idr.c:ida_remove
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff814ca410-ffffffff814ca45c: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814df130)
Location: lib/find_bit.c:102
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:select_task_rq_fair
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
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/isolation.c:bitmap_empty
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/devmap.c:__dev_map_flush
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/events/core.c:perf_output_sample_regs
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:early_pfn_to_nid
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_interleave
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:new_node_page
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
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_ord_to_pos
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
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
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - lib/idr.c:ida_free
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff814df130-ffffffff814df17c: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8150af60)
Location: lib/find_bit.c:98
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/isolation.c:bitmap_empty
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
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
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:kernel_migrate_pages
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
  - mm/memory_hotplug.c:new_node_page
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
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
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
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
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
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/soundwire/bus.c:sdw_handle_slave_alerts
  - drivers/soundwire/bus.c:sdw_handle_slave_alerts
  - drivers/soundwire/bus.c:sdw_handle_slave_alerts
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - lib/idr.c:ida_free
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff8150af60-ffffffff8150af92: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81528d80)
Location: lib/find_bit.c:98
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
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
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/isolation.c:bitmap_empty
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
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
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
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
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
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
  - mm/memory_hotplug.c:new_node_page
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
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
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
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
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
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - lib/idr.c:ida_free
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff81528d80-ffffffff81528db2: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8158c650)
Location: lib/find_bit.c:106
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_swap_config_ts
  - arch/x86/events/intel/p4.c:p4_pmu_swap_config_ts
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:nearby_node
  - arch/x86/kernel/cpu/hygon.c:nearby_node
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_placement
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
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_balance_mask
  - kernel/sched/topology.c:update_top_cache_domain
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/stats.c:schedstat_next
  - kernel/sched/debug.c:sched_debug_next
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/sched/isolation.c:bitmap_empty
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/power/energy_model.c:em_create_pd
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:get_nodes_in_cpumask
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
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
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
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
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:init_kmem_cache_nodes
  - mm/memory_hotplug.c:new_node_page
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
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_remap
  - lib/idr.c:ida_free
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-msic.c:msic_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:pnp_print_irq
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
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
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
**Symbols:**

```
ffffffff8158c650-ffffffff8158c684: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815a90c0)
Location: lib/find_bit.c:108
Inline: False
Direct callers:
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
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_swap_config_ts
  - arch/x86/events/intel/p4.c:p4_pmu_swap_config_ts
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:nearby_node
  - arch/x86/kernel/cpu/hygon.c:nearby_node
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_placement
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
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_balance_mask
  - kernel/sched/topology.c:update_top_cache_domain
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/stats.c:schedstat_next
  - kernel/sched/debug.c:sched_debug_next
  - kernel/sched/debug.c:sd_ctl_doflags
  - kernel/sched/debug.c:sd_ctl_doflags
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/sched/isolation.c:bitmap_empty
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:get_nodes_in_cpumask
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
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
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
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
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
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
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_remap
  - lib/pldmfw/pldmfw.c:pldm_send_component_tables
  - lib/cpumask.c:cpumask_any_distribute
  - lib/idr.c:ida_free
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-msic.c:msic_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:pnp_print_irq
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
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
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
  - net/core/dev.c:dev_change_proto_down_reason
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
  - net/core/devlink.c:__devlink_reload_stats_update
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
**Symbols:**

```
ffffffff815a90c0-ffffffff815a90f4: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008c1c)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/amd/core.c (ffffffff81009b6d)
Location: include/asm-generic/bitops/find.h:109
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100dc53)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:init_hybrid_pmu
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
```
```
In arch/x86/events/intel/ds.c (ffffffff81012969)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
```
```
In arch/x86/events/intel/knc.c (ffffffff8101451c)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810170b9)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101b3f1)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810206d9)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff831bf80f)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81029549)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/hyperv/mmu.c (ffffffff810328b6)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033b22)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/topology.c (ffffffff831c88c2)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049161)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8105090a)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81051318)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054b63)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058e7f)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105af5a)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d420)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060362)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062d5e)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81063399)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106570c)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d39c)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106ea4b)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81071237)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81074ff0)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d8f78)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/kvm.c (ffffffff8107fc48)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/mm/init_64.c (ffffffff831de426)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093c36)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff831dfcc0)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff831e0038)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109aa75)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In kernel/cpu.c (ffffffff810a7c55)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/workqueue.c (ffffffff831e480b)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:__queue_work
```
```
In kernel/reboot.c (ffffffff810d51dd)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810e41a9)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810f735a)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/deadline.c (ffffffff810ff3b3)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/cpupri.c (ffffffff81100902)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff81100e65)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff81103b90)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:update_top_cache_domain
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:sched_domain_debug_one
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
```
```
In kernel/sched/stats.c (ffffffff81105d9f)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff8110648f)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sd_flags_show
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110a069)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
```
In kernel/sched/isolation.c (ffffffff81bd09a8)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/sched/isolation.c:bitmap_empty
```
```
In kernel/power/snapshot.c (ffffffff81114b66)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/power/poweroff.c (ffffffff81117855)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff831e77ae)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff8111edb8)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/resend.c (ffffffff81122040)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/migration.c (ffffffff81128583)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112870b)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/affinity.c (ffffffff81129f18)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8112b9c6)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/time/clocksource.c (ffffffff811493da)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/clocksource.c:clocksource_verify_percpu
```
```
In kernel/time/tick-common.c (ffffffff811543a5)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff81154888)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cgroup.c (ffffffff811753fa)
Location: include/asm-generic/bitops/find.h:109
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
In kernel/cgroup/rdma.c (ffffffff8117a8c4)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f05b)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
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
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
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
```
```
In kernel/stop_machine.c (ffffffff81183fff)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace.c (ffffffff811bda53)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
```
```
In kernel/trace/trace_hwlat.c (ffffffff811caddf)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/verifier.c (ffffffff81208f16)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8122229a)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/events/core.c (ffffffff8123fe00)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
```
```
In kernel/padata.c (ffffffff812582ce)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/watch_queue.c (ffffffff8125b2a5)
Location: include/asm-generic/bitops/find.h:109
Inline: True
```
```
In mm/oom_kill.c (ffffffff81265188)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff831efd35)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
```
```
In mm/mmzone.c (ffffffff81283405)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff831eff50)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/percpu.c (ffffffff831f035f)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/compaction.c (ffffffff831f1bb0)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81295411)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812ba869)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff831f35b5)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/memory_hotplug.c (ffffffff812c6baa)
Location: include/asm-generic/bitops/find.h:109
Inline: True
```
```
In mm/swapfile.c (ffffffff831f45dc)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/frontswap.c (ffffffff812d33a1)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (ffffffff812d9e61)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff812e43a7)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/find.h:109
Inline: False
```
```
In mm/sparse-vmemmap.c (ffffffff81c326ae)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
```
In mm/slub.c (ffffffff812ec1f4)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff831f6c95)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
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
In fs/dcache.c (ffffffff81345488)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/io-wq.c (ffffffff813a22aa)
Location: include/asm-generic/bitops/find.h:109
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
In fs/proc/task_mmu.c (ffffffff813ced58)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff813e2e83)
Location: include/asm-generic/bitops/find.h:109
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffff814e35cc)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff814e7da9)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814f017b)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff814f3f16)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
```
In block/blk-mq.c (ffffffff81577d31)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8157b093)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In lib/bitmap.c (ffffffff815a9613)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
```
```
In lib/pldmfw/pldmfw.c (ffffffff815ee909)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
```
In lib/cpumask.c (ffffffff815f0728)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
```
```
In lib/idr.c (ffffffff815f1bb7)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/nmi_backtrace.c (ffffffff815f5463)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/nodemask.c (ffffffff815f5521)
Location: include/asm-generic/bitops/find.h:109
Inline: True
```
```
In lib/vsprintf.c (ffffffff815fdc18)
Location: include/asm-generic/bitops/find.h:109
Inline: True
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/find.h:109
Inline: False
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8160f8e3)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff816125e8)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81613b36)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81615623)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
```
```
In drivers/gpio/gpiolib.c (ffffffff8161b4ef)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81622ea0)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/search.c (ffffffff81637b4f)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pcie/rcec.c (ffffffff816427e4)
Location: include/asm-generic/bitops/find.h:109
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff81beb193)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/acpi/sysfs.c (ffffffff8320aa11)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
```
In drivers/acpi/x86/apple.c (ffffffff8169bb71)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa/hmat.c (ffffffff816e6cfe)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/pnp/manager.c (ffffffff816f5449)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_irq
```
```
In drivers/pnp/support.c (ffffffff816f6029)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/pnp/support.c:dbg_pnp_show_option
```
```
In drivers/pnp/interface.c (ffffffff816f6529)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/pnp/interface.c:pnp_print_irq
```
```
In drivers/dma/dmaengine.c (ffffffff81705675)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81709890)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
```
```
In drivers/xen/balloon.c (ffffffff8320f289)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/xen/events/events_2l.c (ffffffff81719d67)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a6a1)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81bf808d)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/tty/sysrq.c (ffffffff817430ad)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/tty/vt/keyboard.c (ffffffff81748181)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
```
```
In drivers/char/random.c (ffffffff81770f0b)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/hpet.c (ffffffff81775d96)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_timer_set_irq
```
```
In drivers/iommu/intel/iommu.c (ffffffff81793ee1)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b903)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/base/cacheinfo.c (ffffffff817ba94c)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/node.c (ffffffff817d0e41)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817dd8cf)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/nvdimm/core.c (ffffffff818008b0)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81804553)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:commands_show
```
```
In drivers/nvdimm/label.c (ffffffff8180f8e6)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff818329c7)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/net/phy/phy.c (ffffffff818709f0)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81879430)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d8370)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81904756)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81907fa1)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/input/input.c (ffffffff8191418c)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (ffffffff81917e41)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/misc/uinput.c (ffffffff81920cc2)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8193223e)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In drivers/opp/cpu.c (ffffffff81979e56)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197d165)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81981c6e)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81983405)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In net/core/dev.c (ffffffff819e7ae8)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down_reason
```
```
In net/core/net-sysfs.c (ffffffff81a2176d)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/devlink.c (ffffffff81a4a309)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_reload_stats_update
```
```
In net/ethtool/ioctl.c (ffffffff81a752ba)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
```
```
In net/ethtool/linkmodes.c (ffffffff81a7c194)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
```
In net/ethtool/fec.c (ffffffff81a81a40)
Location: include/asm-generic/bitops/find.h:109
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
```
```
In arch/x86/power/cpu.c (ffffffff81bc2194)
Location: include/asm-generic/bitops/find.h:109
Inline: True
```
**Symbols:**

```
ffffffff811013b0-ffffffff811013bb: find_first_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009a98)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/amd/core.c (ffffffff8100abf3)
Location: include/asm-generic/bitops/find.h:110
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100e2c3)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:init_hybrid_pmu
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
```
```
In arch/x86/events/intel/ds.c (ffffffff81013dd9)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
```
```
In arch/x86/events/intel/knc.c (ffffffff8101589c)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81018d01)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101dd69)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102432d)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8329fd34)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102dce9)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/topology.c (ffffffff832a9b00)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104fb21)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058c8f)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81059812)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105d4b3)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8106203f)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8106449b)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066b20)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106950e)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106cbeb)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106d330)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f80a)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
```
In arch/x86/kernel/smpboot.c (ffffffff81078636)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079a48)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107a3cb)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107cfc7)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810824a0)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc43f)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/kvm.c (ffffffff8108ea28)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/mm/init_64.c (ffffffff832c16b4)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3a16)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff832c325f)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff832c3624)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810aac85)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In kernel/cpu.c (ffffffff810b96b5)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/workqueue.c (ffffffff832c8544)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:__queue_work
```
```
In kernel/reboot.c (ffffffff810e83e0)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810faeb9)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff811118ca)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_group_cpu
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
In kernel/sched/deadline.c (ffffffff8111b397)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/cpupri.c (ffffffff8111c96a)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff8111cfe3)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff81120bb9)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:asym_cpu_capacity_scan
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:update_top_cache_domain
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:sched_domain_debug_one
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
```
```
In kernel/sched/stats.c (ffffffff81123c6f)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff8112413f)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/debug.c:sd_flags_show
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81128607)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
```
In kernel/sched/isolation.c (ffffffff81ca93b0)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/sched/isolation.c:bitmap_empty
```
```
In kernel/power/snapshot.c (ffffffff81134cd3)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/power/poweroff.c (ffffffff81137bb5)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff832cb8a0)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff8113f388)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/resend.c (ffffffff811425f0)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/migration.c (ffffffff81148b53)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81148cdb)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/affinity.c (ffffffff8114a878)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8114c496)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/time/clocksource.c (ffffffff8116cd9a)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
Direct callers:
  - kernel/time/clocksource.c:bitmap_empty
```
```
In kernel/time/tick-common.c (ffffffff81178ba5)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff811792d8)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cgroup.c (ffffffff8119c94c)
Location: include/asm-generic/bitops/find.h:110
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
In kernel/cgroup/rdma.c (ffffffff811a2214)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff811a721b)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
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
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
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
```
```
In kernel/stop_machine.c (ffffffff811ac3af)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace.c (ffffffff811e85a3)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f6e22)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/verifier.c (ffffffff8123ca1b)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81259eb4)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/events/core.c (ffffffff8127a6a0)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
```
```
In kernel/padata.c (ffffffff81293e68)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/watch_queue.c (ffffffff812970ad)
Location: include/asm-generic/bitops/find.h:110
Inline: True
```
```
In mm/oom_kill.c (ffffffff812a19b5)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff832d54ab)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
```
```
In mm/mmzone.c (ffffffff812c1605)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff832d56ca)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/percpu.c (ffffffff832d5b6b)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/compaction.c (ffffffff832d7747)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
```
```
In mm/list_lru.c (ffffffff812d5951)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812fce69)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff832d97e7)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/memory_hotplug.c (ffffffff8130b656)
Location: include/asm-generic/bitops/find.h:110
Inline: True
```
```
In mm/swapfile.c (ffffffff832da898)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/frontswap.c (ffffffff81318e21)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (ffffffff81320a51)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff8132b6c7)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_nodemask
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/find.h:110
Inline: False
```
```
In mm/sparse-vmemmap.c (ffffffff81d50fb0)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
```
```
In mm/slub.c (ffffffff813334de)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/migrate.c (ffffffff8133e2a8)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__disable_all_migrate_targets
```
```
In mm/memcontrol.c (ffffffff832dd82c)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In fs/dcache.c (ffffffff81393098)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/io-wq.c (ffffffff813f3382)
Location: include/asm-generic/bitops/find.h:110
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
In fs/proc/task_mmu.c (ffffffff81420106)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81434993)
Location: include/asm-generic/bitops/find.h:110
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffff8153c9bc)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff815416e9)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8154a6e5)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8154e8bd)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
```
In block/blk-mq.c (ffffffff815dcac3)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff815e03bb)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In lib/bitmap.c (ffffffff81612793)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_ord_to_pos
```
```
In lib/pldmfw/pldmfw.c (ffffffff8165b9b9)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
```
In lib/cpumask.c (ffffffff8165d808)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
```
```
In lib/idr.c (ffffffff8165ed37)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/nmi_backtrace.c (ffffffff816628d3)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/nodemask.c (ffffffff81662987)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In lib/vsprintf.c (ffffffff8166b8e8)
Location: include/asm-generic/bitops/find.h:110
Inline: True
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/find.h:110
Inline: False
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8167e8c8)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff816817e8)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81682c96)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816848d7)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
```
```
In drivers/gpio/gpiolib.c (ffffffff8168aa1d)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81692601)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/search.c (ffffffff816a7de3)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pcie/rcec.c (ffffffff816b34e6)
Location: include/asm-generic/bitops/find.h:110
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff816b65f4)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/acpi/sysfs.c (ffffffff832f2f36)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
```
In drivers/acpi/x86/apple.c (ffffffff81711a26)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa/hmat.c (ffffffff817602d1)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/pnp/manager.c (ffffffff8176fa1d)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_irq
```
```
In drivers/pnp/support.c (ffffffff81770679)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/pnp/support.c:dbg_pnp_show_option
```
```
In drivers/pnp/interface.c (ffffffff81770b89)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/pnp/interface.c:pnp_print_irq
```
```
In drivers/dma/dmaengine.c (ffffffff81780f55)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81785245)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
```
```
In drivers/xen/balloon.c (ffffffff832f81e1)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/xen/events/events_2l.c (ffffffff8179805c)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798e43)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81cf71c5)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/regulator/irq_helpers.c (ffffffff817b2412)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/tty/sysrq.c (ffffffff817c3add)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/tty/vt/keyboard.c (ffffffff817c93a3)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
```
```
In drivers/char/random.c (ffffffff817f6a49)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/hpet.c (ffffffff817fbb06)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_timer_set_irq
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181bd9e)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81824513)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/base/cacheinfo.c (ffffffff818447fc)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/node.c (ffffffff8185b7e1)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81869357)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/nvdimm/core.c (ffffffff8188acb0)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e6d3)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:commands_show
```
```
In drivers/nvdimm/label.c (ffffffff81899e36)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff818bea17)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/net/phy/phy.c (ffffffff81901087)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8190a290)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81973180)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci-hub.c (ffffffff819a4e64)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819a87d0)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/input/input.c (ffffffff819b62a9)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (ffffffff819ba0b1)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/misc/uinput.c (ffffffff819c3a55)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d5585)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In drivers/opp/cpu.c (ffffffff81a22e66)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a261d4)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2af0f)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2c9fa)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In net/core/dev.c (ffffffff81a98efc)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down_reason
```
```
In net/core/net-sysfs.c (ffffffff81ad5ced)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/devlink.c (ffffffff81b02369)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_reload_stats_update
```
```
In net/ethtool/ioctl.c (ffffffff81b3049a)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
```
```
In net/ethtool/linkmodes.c (ffffffff81b364ec)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
```
In net/ethtool/fec.c (ffffffff81b3b713)
Location: include/asm-generic/bitops/find.h:110
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
```
```
In arch/x86/power/cpu.c (ffffffff81c927a4)
Location: include/asm-generic/bitops/find.h:110
Inline: True
```
**Symbols:**

```
ffffffff8111d5d0-ffffffff8111d5db: find_first_bit (STB_LOCAL)
ffffffff8116c9e0-ffffffff8116c9eb: find_first_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005cc9)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff8100f413)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/ds.c (ffffffff81015b17)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
```
In arch/x86/events/intel/p4.c (ffffffff8101aed4)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81032c86)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105b321)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81065613)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81065eca)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8106ea6f)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073851)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810766de)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8107a0ab)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8107a873)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107d0b1)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080c45)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible
```
```
In arch/x86/kernel/smpboot.c (ffffffff81087350)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81088862)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81089415)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_pending_intr_clear
  - arch/x86/kernel/apic/apic.c:apic_pending_intr_clear
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108c657)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81092088)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346dd68)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f4dd)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/mm/init_64.c (ffffffff83473d47)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b8648)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff83475af7)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff83475e32)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810c06f5)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c11f9)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/cpu.c (ffffffff810d00d3)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/workqueue.c (ffffffff8347b650)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/reboot.c (ffffffff81102d29)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff8111953e)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff8112db49)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_group_cpu
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
In kernel/sched/build_policy.c (ffffffff8113afee)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:cpudl_find
```
```
In kernel/sched/build_utility.c (ffffffff8114afa3)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:sched_debug_start
  - kernel/sched/build_utility.c:sugov_kthread_create
Direct callers:
  - kernel/sched/build_utility.c:build_perf_domains
```
```
In kernel/power/snapshot.c (ffffffff81156f70)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/power/poweroff.c (ffffffff8115a215)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/power/energy_model.c (ffffffff8115a997)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdesc.c (ffffffff8347f04c)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff81162e0f)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/resend.c (ffffffff81166140)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/irq_sim.c (ffffffff8116c2fd)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/migration.c (ffffffff8116d68f)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8116d7d7)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/affinity.c (ffffffff8116fe5b)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff81171f06)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/time/clocksource.c (ffffffff811a1143)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff811ade1f)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff811aec40)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff811d82f7)
Location: include/linux/find.h:116
Inline: True
Inline callers:
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
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
```
```
In kernel/stop_machine.c (ffffffff811dddd4)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/pid_list.c (ffffffff8122b703)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_clear
  - kernel/trace/pid_list.c:trace_pid_list_clear
```
```
In kernel/trace/trace_hwlat.c (ffffffff81230683)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff812a2ef1)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff812e9e93)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/watch_queue.c (ffffffff812ecf6d)
Location: include/linux/find.h:116
Inline: True
```
```
In mm/oom_kill.c (ffffffff812f989d)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff83489cdc)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
```
```
In mm/mmzone.c (ffffffff8131e655)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff83489f1a)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/percpu.c (ffffffff8348a404)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/compaction.c (ffffffff8348c2d8)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
```
```
In mm/list_lru.c (ffffffff813352e4)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff81360861)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff8348e78e)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/memory_hotplug.c (ffffffff813740a6)
Location: include/linux/find.h:116
Inline: True
```
```
In mm/swapfile.c (ffffffff8348f9e6)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff8138d745)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff8139b2a8)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:policy_node
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_nodemask
```
```
In mm/sparse.c (0)
Location: include/linux/find.h:116
Inline: False
```
```
In mm/sparse-vmemmap.c (ffffffff81f211cf)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
```
```
In mm/slub.c (ffffffff813a4cc7)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:kmem_cache_init
```
```
In mm/kfence/core.c (ffffffff813af256)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/migrate.c (ffffffff813b10cb)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__disable_all_migrate_targets
```
```
In mm/memcontrol.c (ffffffff83493075)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In mm/hugetlb_cgroup.c (ffffffff813d73c3)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff814147b8)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81498071)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff814aeaea)
Location: include/linux/find.h:116
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffff815d434c)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff815d9849)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff815e3405)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff815e7998)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
```
In block/blk-mq.c (ffffffff8168a704)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8168ede8)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In io_uring/io-wq.c (ffffffff816dbf27)
Location: include/linux/find.h:116
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
In lib/bitmap.c (ffffffff816de8f6)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_ord_to_pos
```
```
In lib/genalloc.c (ffffffff816fb452)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_destroy
```
```
In lib/pldmfw/pldmfw.c (ffffffff81774846)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
```
In lib/cpumask.c (ffffffff81776e13)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
```
```
In lib/idr.c (ffffffff8177861a)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/nmi_backtrace.c (ffffffff8177c73e)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/nodemask.c (ffffffff8177c816)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In lib/xarray.c (0)
Location: include/linux/find.h:116
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff817a7c8d)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pnp/manager.c (ffffffff818a4e51)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_irq
```
```
In drivers/pnp/support.c (ffffffff818a5b81)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/pnp/support.c:dbg_pnp_show_option
```
```
In drivers/pnp/interface.c (ffffffff818a60da)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/pnp/interface.c:pnp_print_irq
```
```
In drivers/xen/grant-table.c (ffffffff818c7461)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_seq
```
```
In drivers/xen/balloon.c (ffffffff834b0900)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/xen/events/events_2l.c (ffffffff818d1380)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d2007)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/n_tty.c (ffffffff818f630a)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
```
In drivers/tty/sysrq.c (ffffffff8190082d)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/iommu/intel/iommu.c (ffffffff834b8527)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8196428c)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/base/cacheinfo.c (ffffffff81988a44)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/node.c (ffffffff834baa48)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_read_distance
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d926e)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/net/phy/phy.c (ffffffff81a53a0a)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d9b2)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/opp/cpu.c (ffffffff81b8bf7f)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b914f2)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq.c:show
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b9531f)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b9822c)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In drivers/devfreq/governor_passive.c (ffffffff81bd653e)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_parent_cpu_data
```
```
In net/core/net-sysfs.c (ffffffff81c56515)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ethtool/ioctl.c (ffffffff81cbbb67)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
```
```
In net/ethtool/linkmodes.c (ffffffff81cc1e2c)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
```
In net/ethtool/fec.c (ffffffff81cc7715)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
```
```
In net/ncsi/ncsi-manage.c (ffffffff81e1333a)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In arch/x86/power/cpu.c (ffffffff81e41f5d)
Location: include/linux/find.h:116
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
```
**Symbols:**

```
ffffffff81e56958-ffffffff81e5696b: find_first_bit (STB_LOCAL)
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
In arch/x86/events/core.c (ffffffff81007629)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff81012dd3)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/ds.c (ffffffff810191b5)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
```
In arch/x86/events/intel/p4.c (ffffffff8101f054)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a602)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81068cd1)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81074914)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81075206)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8107cea1)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8107ed5f)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81083349)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083c61)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810861ce)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108b1b5)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108bad0)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e2d6)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810939b5)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109a9e8)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c370)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109d279)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a0bd7)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810a7078)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e93abd)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6d4d)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/mm/init_64.c (ffffffff83e9b997)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d3902)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:leave_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff83e9e8c5)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff83e9ebbc)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810dc695)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dd9d3)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/cpu.c (ffffffff810ee765)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/workqueue.c (ffffffff83ea64d8)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/reboot.c (ffffffff811281e9)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff81140e0e)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff81157949)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_cpu_capacity
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/build_policy.c (ffffffff81165920)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:cpudl_find
```
```
In kernel/sched/build_utility.c (ffffffff811799c3)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:sched_debug_start
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/power/snapshot.c (ffffffff81187cab)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/power/poweroff.c (ffffffff8118c515)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/power/energy_model.c (ffffffff8118cd89)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdesc.c (ffffffff83eab325)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/manage.c (ffffffff811969ef)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/resend.c (ffffffff8119a290)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/irq_sim.c (ffffffff811a1285)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/migration.c (ffffffff811a282f)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a2997)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/affinity.c (ffffffff811a62bb)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff811a85f8)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/time/clocksource.c (ffffffff811e0063)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff811ee45f)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff811eedf3)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff8121ed0c)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
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
  - kernel/cgroup/cpuset.c:node_random
```
```
In kernel/stop_machine.c (ffffffff812238b6)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/pid_list.c (ffffffff812770e3)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_clear
  - kernel/trace/pid_list.c:trace_pid_list_clear
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127ccf7)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/percpu_freelist.c (ffffffff812ffaac)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81300a1d)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff81353df3)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/watch_queue.c (ffffffff813572ed)
Location: include/linux/find.h:165
Inline: True
```
```
In mm/oom_kill.c (ffffffff8136346d)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff83eba5bf)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_del_mm
  - mm/vmscan.c:lru_gen_add_mm
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
```
```
In mm/mmzone.c (ffffffff81392155)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff83eba864)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/percpu.c (ffffffff83ebae8d)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/compaction.c (ffffffff83ebd5de)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
```
```
In mm/list_lru.c (ffffffff813abfa4)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff813dbd71)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff83ec09c5)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/memory_hotplug.c (ffffffff813f1b4c)
Location: include/linux/find.h:165
Inline: True
```
```
In mm/swapfile.c (ffffffff83ec218d)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff83ec3a09)
Location: include/linux/find.h:165
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8141b328)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:policy_node
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_nodemask
```
```
In mm/sparse.c (0)
Location: include/linux/find.h:165
Inline: False
```
```
In mm/sparse-vmemmap.c (ffffffff820cae9c)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
```
```
In mm/slub.c (ffffffff81424f84)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/kfence/core.c (ffffffff8142f81a)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/memory-tiers.c (ffffffff83ec699c)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:memtier_hotplug_callback
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:next_demotion_node
```
```
In mm/khugepaged.c (ffffffff81447e2f)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff83ec6fd0)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In mm/hugetlb_cgroup.c (ffffffff8145c6ec)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff8149fc98)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8152bdea)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81545180)
Location: include/linux/find.h:165
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffff8168248c)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff81687628)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8169267a)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff81697088)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
```
In block/blk-mq.c (ffffffff81748d06)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8174d893)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In io_uring/io-wq.c (ffffffff817a8037)
Location: include/linux/find.h:165
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
In lib/genalloc.c (ffffffff817ee042)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_destroy
```
```
In lib/pldmfw/pldmfw.c (ffffffff818a46aa)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_send_component_tables
```
```
In drivers/gpio/gpiolib.c (ffffffff818c0281)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pnp/manager.c (ffffffff819eec3a)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_irq
```
```
In drivers/pnp/support.c (ffffffff819efa51)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/pnp/support.c:dbg_pnp_show_option
```
```
In drivers/pnp/interface.c (ffffffff819efffa)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/pnp/interface.c:pnp_print_irq
```
```
In drivers/xen/grant-table.c (ffffffff81a17fa1)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_seq
```
```
In drivers/xen/balloon.c (ffffffff83eea6b9)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/xen/events/events_2l.c (ffffffff81a22ca0)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a23b5e)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/n_tty.c (ffffffff81a4ed0e)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
```
In drivers/tty/sysrq.c (ffffffff81a5a46d)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff81a94efc)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/iommu/intel/iommu.c (ffffffff83ef5240)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acd31c)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/base/cacheinfo.c (ffffffff81af7624)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/node.c (ffffffff83ef835c)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_read_distance
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b542de)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/net/phy/phy.c (ffffffff81bdd0de)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81be859a)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/opp/cpu.c (ffffffff81d2b80c)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d317f2)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq.c:show
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d35baf)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d39048)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In drivers/devfreq/governor_passive.c (ffffffff81d82c8a)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_parent_cpu_data
```
```
In net/core/net-sysfs.c (ffffffff81e0bfc9)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ethtool/ioctl.c (ffffffff81e7a127)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
```
```
In net/ethtool/linkmodes.c (ffffffff81e80c0c)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
```
In net/ethtool/fec.c (ffffffff81e86d85)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
```
```
In net/ncsi/ncsi-manage.c (ffffffff81fea012)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In arch/x86/power/cpu.c (ffffffff8201c72d)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
```
```
In lib/cpumask.c (ffffffff8201f87b)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
```
```
In lib/idr.c (ffffffff820213a0)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/nmi_backtrace.c (ffffffff8203920e)
Location: include/linux/find.h:165
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/xarray.c (0)
Location: include/linux/find.h:165
Inline: False
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
In arch/x86/events/core.c (ffffffff81006e33)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff810123a3)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/ds.c (ffffffff81018bf5)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
```
In arch/x86/events/intel/p4.c (ffffffff8101ed43)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a6d2)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a5e1)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107685c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81077376)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8107f251)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81080edf)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810857f9)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81086201)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089b23)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108e255)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108e9fa)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81091186)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096935)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/kernel/smp.c (ffffffff8109b8ed)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109ded8)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f778)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a0231)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a3bc7)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810aa2d8)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b776d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9eed)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/mm/init_64.c (ffffffff836bf437)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6ce2)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:leave_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff836c2a25)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff836c2d30)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810e7c65)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e9049)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/cpu.c (ffffffff810fa745)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/workqueue.c (ffffffff836cac98)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/reboot.c (ffffffff81135699)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff8114cb2e)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff81167999)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/build_policy.c (ffffffff811760e0)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:cpudl_find
```
```
In kernel/sched/build_utility.c (ffffffff8118a4d3)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:sched_debug_start
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/power/snapshot.c (ffffffff81198e3b)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/power/poweroff.c (ffffffff8119dc35)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/power/energy_model.c (ffffffff8119e52c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdesc.c (ffffffff836d030d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/manage.c (ffffffff811a83af)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/irq_sim.c (ffffffff811b3095)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/migration.c (ffffffff811b472f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b4897)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/matrix.c (ffffffff811ba2c8)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/time/clocksource.c (ffffffff811f452a)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff81202b8f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff81203b90)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff81234e04)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach_check
  - kernel/cgroup/cpuset.c:cpuset_can_attach_check
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
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
```
```
In kernel/stop_machine.c (ffffffff81239f46)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace.c (ffffffff8127eacd)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In kernel/trace/pid_list.c (ffffffff8128ead3)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_clear
  - kernel/trace/pid_list.c:trace_pid_list_clear
```
```
In kernel/trace/trace_hwlat.c (ffffffff812949de)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8132e60c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8132f57a)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/bpf/cpumask.c (ffffffff8135da90)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_empty
  - kernel/bpf/cpumask.c:bpf_cpumask_first
```
```
In kernel/padata.c (ffffffff81384ff3)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/watch_queue.c (ffffffff81388b6a)
Location: include/linux/find.h:200
Inline: True
```
```
In mm/oom_kill.c (ffffffff813958bd)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff836dfbcf)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_release_memcg
  - mm/vmscan.c:lru_gen_offline_memcg
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_del_mm
  - mm/vmscan.c:lru_gen_add_mm
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
```
```
In mm/mmzone.c (ffffffff813c4b55)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff836dfe74)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffff836e2fa8)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:page_alloc_init_late
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:early_pfn_to_nid
```
```
In mm/percpu.c (ffffffff836e34b2)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/compaction.c (ffffffff836e5a8e)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/show_mem.c (ffffffff813de776)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/show_mem.c:__show_free_areas
```
```
In mm/list_lru.c (ffffffff813e0344)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff81410611)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
  - mm/vmalloc.c:vmap_ram_vread_iter
```
```
In mm/page_alloc.c (ffffffff81422a94)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/memory_hotplug.c (ffffffff814255ec)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swapfile.c (ffffffff836e777d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff836e8ae9)
Location: include/linux/find.h:200
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8144e8d8)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:policy_node
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_nodemask
```
```
In mm/sparse.c (0)
Location: include/linux/find.h:200
Inline: False
```
```
In mm/sparse-vmemmap.c (ffffffff8214f12d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
```
```
In mm/slub.c (ffffffff8145a334)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/kfence/core.c (ffffffff81464a3a)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/memory-tiers.c (ffffffff836eb98c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:memtier_hotplug_callback
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:next_demotion_node
```
```
In mm/khugepaged.c (ffffffff8147d7df)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff836ebfe0)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In mm/hugetlb_cgroup.c (ffffffff8149234c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff814d4fb8)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8156415b)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff8157cd60)
Location: include/linux/find.h:200
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffff816ba60c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff816bf9f9)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff816cabe7)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff816cf597)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
```
In block/blk-mq.c (ffffffff8178541b)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
```
```
In lib/genalloc.c (ffffffff8182e452)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_destroy
```
```
In lib/group_cpus.c (ffffffff818e6cee)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
  - lib/group_cpus.c:grp_spread_init_one
```
```
In lib/pldmfw/pldmfw.c (ffffffff818e74ea)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_send_component_tables
```
```
In drivers/gpio/gpiolib.c (ffffffff8190325f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pnp/manager.c (ffffffff81a3740a)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_irq
```
```
In drivers/pnp/support.c (ffffffff81a381ad)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/pnp/support.c:dbg_pnp_show_option
```
```
In drivers/pnp/interface.c (ffffffff81a386fa)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/pnp/interface.c:pnp_print_irq
```
```
In drivers/xen/grant-table.c (ffffffff81a61031)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_seq
```
```
In drivers/xen/balloon.c (ffffffff837100aa)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/xen/events/events_2l.c (ffffffff81a6bf4e)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6d01e)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/n_tty.c (ffffffff81a9911c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
```
In drivers/tty/sysrq.c (ffffffff81aa4a9d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff81ae071f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/iommu/intel/iommu.c (ffffffff8371ad9f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19e8c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1af22)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_online
```
```
In drivers/base/cacheinfo.c (ffffffff81b45864)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/node.c (ffffffff8371defc)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_read_distance
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba782e)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/net/phy/phy.c (ffffffff81c328db)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81c36848)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3c7e8)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81c4093b)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/net/virtio_net.c (ffffffff81c4ce02)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/opp/cpu.c (ffffffff81d94abc)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9abb2)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq.c:show
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9ef1f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da3ae8)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In drivers/devfreq/governor_passive.c (ffffffff81df106a)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_parent_cpu_data
```
```
In net/core/net-sysfs.c (ffffffff81e8183d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
```
```
In net/ethtool/ioctl.c (ffffffff81ed6427)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
```
```
In net/ethtool/linkmodes.c (ffffffff81edd5ac)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
```
In net/ethtool/fec.c (ffffffff81ee38c9)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
```
```
In net/ncsi/ncsi-manage.c (ffffffff820661cc)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In arch/x86/power/cpu.c (ffffffff8209cdbd)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
```
```
In lib/cpumask.c (ffffffff8209f88b)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
```
```
In lib/idr.c (ffffffff820a13d0)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/nmi_backtrace.c (ffffffff820b751e)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/xarray.c (0)
Location: include/linux/find.h:200
Inline: False
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
In arch/x86/events/core.c (ffffffff8100c562)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff81017cc3)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/ds.c (ffffffff8101e755)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
```
In arch/x86/events/intel/p4.c (ffffffff81024e03)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81040b92)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81071ab1)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107ddff)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e91c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81086d61)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810889ef)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c84b)
Location: include/linux/find.h:200
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d0e1)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090c3c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810955e5)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81095d8a)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098546)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109dea5)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/kernel/smp.c (ffffffff810a2e8d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a5503)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6c08)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a7864)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810aabf7)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810b1368)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e80b5)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/kvm.c (ffffffff810c12ad)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/mm/init_64.c (ffffffff838efed7)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df512)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:leave_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff838f3445)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff838f3920)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810efff5)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f13fd)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/cpu.c (ffffffff81103b65)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/workqueue.c (ffffffff8112dc08)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_calc_pod_cpumask
  - kernel/workqueue.c:wq_calc_pod_cpumask
  - kernel/workqueue.c:wqattrs_actualize_cpumask
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/reboot.c (ffffffff811406f9)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff811587ee)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff81174799)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/build_policy.c (ffffffff8118436e)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:cpudl_find
```
```
In kernel/sched/build_utility.c (ffffffff81198dd3)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:init_sched_groups_capacity
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/power/snapshot.c (ffffffff811a7dc7)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/power/poweroff.c (ffffffff811acda5)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/power/energy_model.c (ffffffff811ad6ec)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdesc.c (ffffffff8390172d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/manage.c (ffffffff811b7e2f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/irq_sim.c (ffffffff811c2eb5)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/migration.c (ffffffff811c45af)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c4717)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/matrix.c (ffffffff811ca188)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/rcu/tree.c (ffffffff839039d0)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/time/hrtimer.c (ffffffff81205515)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_cpu_dying
```
```
In kernel/time/clocksource.c (ffffffff8120a66c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff8121914f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff8121a150)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ea24)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach_check
  - kernel/cgroup/cpuset.c:cpuset_can_attach_check
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:remote_cpus_update
  - kernel/cgroup/cpuset.c:reset_partition_data
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/stop_machine.c (ffffffff81253c16)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace.c (ffffffff81299594)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In kernel/trace/pid_list.c (ffffffff812a9fa3)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_clear
  - kernel/trace/pid_list.c:trace_pid_list_clear
```
```
In kernel/trace/trace_hwlat.c (ffffffff812b003e)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c8348)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81352b2c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81353a9a)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/bpf/cpumask.c (ffffffff81386830)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_empty
  - kernel/bpf/cpumask.c:bpf_cpumask_first
```
```
In kernel/padata.c (ffffffff813ae362)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/watch_queue.c (ffffffff813b25ca)
Location: include/linux/find.h:200
Inline: True
```
```
In mm/oom_kill.c (ffffffff813bf67d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff8391244f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_release_memcg
  - mm/vmscan.c:lru_gen_offline_memcg
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_del_mm
  - mm/vmscan.c:lru_gen_add_mm
  - mm/vmscan.c:drop_slab
```
```
In mm/shrinker.c (ffffffff813e4bc7)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/shrinker.c:reparent_shrinker_deferred
  - mm/shrinker.c:expand_one_shrinker_info
  - mm/shrinker.c:alloc_shrinker_info
  - mm/shrinker.c:free_shrinker_info
```
```
In mm/mmzone.c (ffffffff813ef575)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff83912724)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffff83915838)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:page_alloc_init_late
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:early_pfn_to_nid
```
```
In mm/percpu.c (ffffffff83915d42)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/compaction.c (ffffffff839182be)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/show_mem.c (ffffffff81408566)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/show_mem.c:show_free_areas
```
```
In mm/list_lru.c (ffffffff8140a6a4)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff8143cf71)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
  - mm/vmalloc.c:vmap_ram_vread_iter
```
```
In mm/page_alloc.c (ffffffff8144f884)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/memory_hotplug.c (ffffffff814528f4)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/slub.c (ffffffff81455404)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/swapfile.c (ffffffff8391a80d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/zswap.c (ffffffff8146f198)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/zswap.c:shrink_memcg
```
```
In mm/hugetlb.c (ffffffff8391c079)
Location: include/linux/find.h:200
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81488478)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:policy_nodemask
  - mm/mempolicy.c:interleave_nid
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_nodemask
```
```
In mm/sparse.c (0)
Location: include/linux/find.h:200
Inline: False
```
```
In mm/sparse-vmemmap.c (ffffffff82231ffd)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
```
```
In mm/kfence/core.c (ffffffff8149410f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_late
  - mm/kfence/core.c:kfence_init_late
```
```
In mm/memory-tiers.c (ffffffff8391e5bd)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:memtier_hotplug_callback
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:next_demotion_node
```
```
In mm/khugepaged.c (ffffffff814abbaf)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff8391efa0)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In mm/hugetlb_cgroup.c (ffffffff814c1d5c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff815073b8)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8159afcf)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff815b5680)
Location: include/linux/find.h:200
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffff816f709c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff816fc239)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81707826)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8170bbb7)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
```
In block/blk-mq.c (ffffffff817c7967)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
```
```
In lib/genalloc.c (ffffffff81880012)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_destroy
```
```
In lib/group_cpus.c (ffffffff8192dd0e)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
  - lib/group_cpus.c:grp_spread_init_one
```
```
In lib/pldmfw/pldmfw.c (ffffffff8192e52a)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_send_component_tables
```
```
In drivers/gpio/gpiolib.c (ffffffff8194ae07)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/acpi/numa/hmat.c (ffffffff8393f668)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
```
```
In drivers/pnp/manager.c (ffffffff81a82bca)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_irq
```
```
In drivers/pnp/support.c (ffffffff81a8396d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/pnp/support.c:dbg_pnp_show_option
```
```
In drivers/pnp/interface.c (ffffffff81a83eea)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/pnp/interface.c:pnp_print_irq
```
```
In drivers/xen/grant-table.c (ffffffff81ab3861)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_seq
```
```
In drivers/xen/balloon.c (ffffffff83943a1f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/xen/events/events_2l.c (ffffffff81abe006)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abf1e4)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/n_tty.c (ffffffff81aeb7bc)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
```
In drivers/tty/sysrq.c (ffffffff81af749d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff81b33b1f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/iommu/intel/iommu.c (ffffffff8394e87f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6fae6)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b70a52)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_online
```
```
In drivers/base/cacheinfo.c (ffffffff81b9d8e4)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/node.c (ffffffff839518cc)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_read_distance
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfbb0d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/net/phy/phy.c (ffffffff81ce75cb)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81ceb7c8)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf1be8)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81cf5f9b)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/net/virtio_net.c (ffffffff81d026a2)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/opp/cpu.c (ffffffff81e4c5cc)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e52928)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq.c:show
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e56d2f)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5bb78)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In drivers/devfreq/governor_passive.c (ffffffff81ea76b9)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_parent_cpu_data
```
```
In net/core/net-sysfs.c (ffffffff81f4281d)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
```
```
In net/ethtool/ioctl.c (ffffffff81f99fa7)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
  - net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd
```
```
In net/ethtool/linkmodes.c (ffffffff81fa137c)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
```
In net/ethtool/fec.c (ffffffff81fa76a9)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:ethtool_link_modes_to_fecparam
```
```
In net/ncsi/ncsi-manage.c (ffffffff82139380)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In arch/x86/power/cpu.c (ffffffff821745bd)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
```
```
In lib/cpumask.c (ffffffff821778eb)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
```
```
In lib/idr.c (ffffffff8217933b)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/nmi_backtrace.c (ffffffff821916ce)
Location: include/linux/find.h:200
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/xarray.c (0)
Location: include/linux/find.h:200
Inline: False
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81521360)
Location: lib/find_bit.c:98
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
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
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/isolation.c:bitmap_empty
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
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
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
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
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
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
  - mm/memory_hotplug.c:new_node_page
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
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_mpath_clear_current_path
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
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
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
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
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - lib/idr.c:ida_free
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff81521360-ffffffff81521392: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81511650)
Location: lib/find_bit.c:98
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
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
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/isolation.c:bitmap_empty
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
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
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
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
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
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
  - mm/memory_hotplug.c:new_node_page
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
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_add_dimm
  - drivers/acpi/nfit/core.c:acpi_nfit_add_dimm
  - drivers/acpi/nfit/core.c:acpi_nfit_add_dimm
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_mpath_clear_current_path
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
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
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/hv/vmbus_drv.c:vmbus_isr
  - drivers/hv/channel_mgmt.c:init_vp_index
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - lib/idr.c:ida_free
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff81511650-ffffffff81511682: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8151d3f0)
Location: lib/find_bit.c:98
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
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
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/isolation.c:bitmap_empty
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
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
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
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
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
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
  - mm/memory_hotplug.c:new_node_page
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
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
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
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
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
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - lib/idr.c:ida_free
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff8151d3f0-ffffffff8151d422: find_first_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81536c60)
Location: lib/find_bit.c:98
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
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
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/isolation.c:bitmap_empty
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
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
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:drop_slab
  - mm/mmzone.c:first_online_pgdat
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
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
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
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
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
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
  - mm/memory_hotplug.c:new_node_page
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
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:dbg_pnp_show_option
  - drivers/pnp/interface.c:options_show
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/sysrq.c:moom_callback
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/hpet.c:hpet_open
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
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
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
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
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - lib/idr.c:ida_free
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
ffffffff81536c60-ffffffff81536c92: find_first_bit (STB_GLOBAL)
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
