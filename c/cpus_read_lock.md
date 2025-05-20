# Function: <code>cpus_read_lock</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810866c1)
Location: kernel/cpu.c:216
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:lockup_detector_suspend
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swap.c:lru_add_drain_all
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_deactivate_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:rollback_registered_many
  - net/core/flow.c:flow_cache_flush
```
**Symbols:**

```
ffffffff81085380-ffffffff810853b4: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108d321)
Location: kernel/cpu.c:291
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/membarrier.c:SyS_membarrier
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/swap.c:lru_add_drain_all
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_deactivate_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
```
**Symbols:**

```
ffffffff8108c020-ffffffff8108c054: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81090c85)
Location: kernel/cpu.c:288
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_deactivate_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
```
**Symbols:**

```
ffffffff8108f9f0-ffffffff8108fa24: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81098d45)
Location: kernel/cpu.c:286
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_deactivate_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:__remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff81097d10-ffffffff81097d44: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d2c5)
Location: kernel/cpu.c:287
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/power/suspend.c:suspend_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff8109c2c0-ffffffff8109c2f4: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3815)
Location: kernel/cpu.c:290
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/power/suspend.c:suspend_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff810a2810-ffffffff810a2844: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aa8b5)
Location: kernel/cpu.c:291
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/power/suspend.c:s2idle_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:disarm_all_kprobes
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:unoptimize_all_kprobes
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:store_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff810a93d0-ffffffff810a9404: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6145)
Location: kernel/cpu.c:291
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_get_topology
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/power/suspend.c:s2idle_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:disarm_all_kprobes
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:unoptimize_all_kprobes
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:static_call_init
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:store_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff810a4e20-ffffffff810a4e54: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6f95)
Location: kernel/cpu.c:296
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/power/suspend.c:s2idle_loop
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:static_call_init
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff810a5b20-ffffffff810a5b54: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b8935)
Location: kernel/cpu.c:307
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/power/suspend.c:s2idle_loop
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/trace_hwlat.c:hwlat_hotplug_workfn
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:static_call_init
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
  - mm/slab_common.c:kmem_cache_destroy
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:__kmem_cache_shrink
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff810b74b0-ffffffff810b74e4: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cf1f5)
Location: kernel/cpu.c:308
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/power/suspend.c:s2idle_loop
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/trace_hwlat.c:hwlat_hotplug_workfn
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:static_call_init
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
  - mm/slab_common.c:kmem_cache_destroy
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:__kmem_cache_shrink
  - mm/migrate.c:migrate_on_reclaim_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff810ce1b0-ffffffff810ce20f: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ed665)
Location: kernel/cpu.c:308
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/power/suspend.c:s2idle_loop
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/trace_hwlat.c:hwlat_hotplug_workfn
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:static_call_init
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
  - mm/slab_common.c:kmem_cache_destroy
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:__kmem_cache_shrink
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff810ec340-ffffffff810ec39f: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f91f5)
Location: kernel/cpu.c:487
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:sched_verbose_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/power/suspend.c:s2idle_loop
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
  - kernel/cgroup/legacy_freezer.c:freezer_css_online
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/trace_hwlat.c:hwlat_hotplug_workfn
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
  - kernel/trace/trace_osnoise.c:osnoise_options_write
  - kernel/trace/trace_osnoise.c:osnoise_hotplug_workfn
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:stop_per_cpu_kthreads
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:static_call_init
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
  - mm/slab_common.c:kmem_cache_destroy
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:__kmem_cache_shrink
  - lib/group_cpus.c:group_cpus_evenly
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_set_channels
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff810f7e70-ffffffff810f7ecf: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81102605)
Location: kernel/cpu.c:487
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_affinity_strict_store
  - kernel/workqueue.c:wq_affn_scope_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_affn_dfl_set
  - kernel/workqueue.c:work_on_cpu_safe_key
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:sched_verbose_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/power/suspend.c:s2idle_loop
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/tree.c:rcu_nocb_cpu_offload
  - kernel/rcu/tree.c:rcu_nocb_cpu_deoffload
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
  - kernel/cgroup/legacy_freezer.c:freezer_css_online
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/trace_hwlat.c:hwlat_hotplug_workfn
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
  - kernel/trace/trace_osnoise.c:osnoise_options_write
  - kernel/trace/trace_osnoise.c:osnoise_hotplug_workfn
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:stop_per_cpu_kthreads
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:static_call_init
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
  - mm/slab_common.c:kmem_cache_destroy
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:__kmem_cache_shrink
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/net/virtio_net.c:virtnet_set_channels
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:store_local_boost
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch
```
**Symbols:**

```
ffffffff81101280-ffffffff811012df: cpus_read_lock (STB_GLOBAL)
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
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9050)
Location: kernel/cpu.c:290
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/power/suspend.c:s2idle_loop
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:arm_kprobe
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffff8000100f7a38-ffff8000100f7a8c: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0357270)
Location: kernel/cpu.c:290
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
c0355eb0-c0355f04: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013fca8)
Location: kernel/cpu.c:290
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan
  - arch/powerpc/mm/book3s64/hash_utils.c:hpt_order_set
  - arch/powerpc/platforms/powernv/subcore.c:set_subcores_per_core
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_core_pmu_counters
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters
  - arch/powerpc/platforms/pseries/mobility.c:post_mobility_fixup
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvm_hv_vm_deactivated
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvm_hv_vm_activated
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
c00000000013e520-c00000000013e5b0: cpus_read_lock (STB_GLOBAL)
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
In kernel/cpu.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpu.h:126
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpu.h:126
Inline: True
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
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d135)
Location: kernel/cpu.c:290
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff8109c130-ffffffff8109c164: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108bb65)
Location: kernel/cpu.c:290
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff8108ab60-ffffffff8108ab94: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d0e5)
Location: kernel/cpu.c:290
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/power/suspend.c:suspend_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff8109c0e0-ffffffff8109c114: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cpus_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4f15)
Location: kernel/cpu.c:290
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/events/intel/core.c:intel_sandybridge_quirk
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/power/suspend.c:suspend_enter
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
  - kernel/jump_label.c:static_key_slow_inc
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/swap_slots.c:disable_swap_slots_cache_lock
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff810a3f10-ffffffff810a3f56: cpus_read_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
