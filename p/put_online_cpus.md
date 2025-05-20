# Function: <code>put_online_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void put_online_cpus();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081360)
Location: kernel/cpu.c:105
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:lockup_detector_resume
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_set_cpumasks
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_add_cpu
  - kernel/padata.c:padata_remove_cpu
  - mm/swap.c:lru_add_drain_all
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_cpuup_callback
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/memcontrol.c:try_charge
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed
  - drivers/net/virtio_net.c:virtnet_set_channels
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/core/flow.c:flow_cache_flush
```
**Symbols:**

```
ffffffff81081360-ffffffff810813d0: put_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void put_online_cpus();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81083fb0)
Location: kernel/cpu.c:182
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/irq/affinity.c:irq_create_affinity_mask
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:lockup_detector_resume
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - mm/swap.c:lru_add_drain_all
  - mm/vmstat.c:vmstat_cpuup_callback
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/net/virtio_net.c:virtnet_set_channels
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - net/core/flow.c:flow_cache_flush
```
**Symbols:**

```
ffffffff81083fb0-ffffffff81084024: put_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void put_online_cpus();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810884e0)
Location: kernel/cpu.c:248
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
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
  - kernel/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_machine
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:lockup_detector_resume
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - mm/swap.c:lru_add_drain_all
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - net/core/dev.c:rollback_registered_many
  - net/core/flow.c:flow_cache_flush
```
**Symbols:**

```
ffffffff810884e0-ffffffff81088554: put_online_cpus (STB_GLOBAL)
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
In arch/x86/events/intel/core.c (ffffffff8100ace2)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e6e7)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff820a3085)
Location: include/linux/cpu.h:127
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042d76)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104cf24)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ee21)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107824f)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810a1762)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810a9bc2)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
```
In kernel/sched/core.c (ffffffff810af662)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810d8ca8)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (ffffffff810efdc5)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff810f45de)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/livepatch/transition.c (ffffffff810f8f3e)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff8112df3a)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/watchdog.c (ffffffff8114f518)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:lockup_detector_resume
```
```
In kernel/trace/ring_buffer.c (ffffffff8115e2ee)
Location: include/linux/cpu.h:127
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811709be)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff811afc57)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff811b3f6d)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/swap.c (ffffffff811cc813)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/vmstat.c (ffffffff820d09e7)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff811e61e6)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_deactivate_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
```
```
In mm/swap_slots.c (ffffffff811ec791)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In mm/memcontrol.c (ffffffff8123cf98)
Location: include/linux/cpu.h:127
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81530f8b)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81766057)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81768415)
Location: include/linux/cpu.h:127
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817696ba)
Location: include/linux/cpu.h:127
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176c40b)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff817ca558)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/flow.c (ffffffff817ef111)
Location: include/linux/cpu.h:127
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
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
In arch/x86/events/intel/core.c (ffffffff8100b2a2)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff826a936f)
Location: include/linux/cpu.h:125
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8105081a)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105277c)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107e5ab)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810a7fc2)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810b0229)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
```
In kernel/sched/core.c (ffffffff810b6942)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810e0fed)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (ffffffff810f8975)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff810fe4a2)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/livepatch/transition.c (ffffffff811038ec)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff8113aaca)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ring_buffer.c (ffffffff8116b29e)
Location: include/linux/cpu.h:125
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff8117db81)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff811c37d5)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff811c7bfd)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/swap.c (ffffffff811e1833)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/vmstat.c (ffffffff826d941e)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff811fc426)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_deactivate_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
```
```
In mm/swap_slots.c (ffffffff81202b01)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff81591f9d)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817dc023)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817de305)
Location: include/linux/cpu.h:125
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817df450)
Location: include/linux/cpu.h:125
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e2259)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff8184403f)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f9b66)
Location: include/linux/cpu.h:125
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
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
In arch/x86/events/intel/core.c (ffffffff8100b9b6)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff826d24f4)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053468)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810554a1)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81081611)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810aeb72)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810b7039)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
```
In kernel/sched/core.c (ffffffff810bc660)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810e959e)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (ffffffff81100ef0)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff811053cb)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/livepatch/transition.c (ffffffff8110beeb)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff81149a98)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ring_buffer.c (ffffffff8117a3e2)
Location: include/linux/cpu.h:129
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff8118c9c9)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff811e3ab1)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff811e7e3d)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff827038ac)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff8121d586)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_deactivate_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (ffffffff8124ea61)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff815c9332)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81824cd3)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81826fd5)
Location: include/linux/cpu.h:129
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81829414)
Location: include/linux/cpu.h:129
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182b039)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff81897f7e)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/xfrm/xfrm_policy.c (ffffffff819505fe)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ba76)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff82888804)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81050ae8)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052b41)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81088221)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810b7cd2)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810c04b9)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810c4e40)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810f4bbe)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (ffffffff8110c7f8)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff81110bf8)
Location: include/linux/cpu.h:131
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff811176db)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff81155b3d)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ring_buffer.c (ffffffff811873b2)
Location: include/linux/cpu.h:131
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119a4d9)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff811f3f81)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff811f8e0d)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828bafd5)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff81230576)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_deactivate_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (ffffffff81262f41)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff815e2902)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81850c63)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81852ed5)
Location: include/linux/cpu.h:131
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81853e44)
Location: include/linux/cpu.h:131
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81856fa9)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff818ba2c0)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100be03)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff8289f97f)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053baa)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055cf3)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108be70)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810bd762)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810c65bc)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810ce4fa)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810fce94)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/affinity.c (ffffffff81115ef5)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff8111a661)
Location: include/linux/cpu.h:133
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff811219c0)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff81163064)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ring_buffer.c (ffffffff811947a8)
Location: include/linux/cpu.h:133
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a8141)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120bc5f)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81210b59)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828d2437)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff81240588)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (ffffffff8127deb1)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff8161448d)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818941a3)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81896495)
Location: include/linux/cpu.h:133
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8189791b)
Location: include/linux/cpu.h:133
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8189a6f7)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff818fc77b)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c213)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff828a2a51)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105449a)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056633)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108cada)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810c3d42)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810cf69c)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810d80fa)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff81109300)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/affinity.c (ffffffff811222d5)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff81126a6d)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8112dfe0)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff81170625)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
```
In kernel/trace/ring_buffer.c (ffffffff811a0268)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b3941)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff81218f3f)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff8121da04)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828da8a9)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff812508c5)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (ffffffff8128d901)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff8163597d)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c61c3)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c84a5)
Location: include/linux/cpu.h:138
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c9ebc)
Location: include/linux/cpu.h:138
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818cc8a7)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff8192eda9)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d3c3)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff82cc8c7b)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105952a)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b8c0)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093cfe)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In kernel/workqueue.c (ffffffff810cba5d)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810d922c)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810df446)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff81113cfa)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_enter
```
```
In kernel/irq/affinity.c (ffffffff8112e8f5)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff811366ed)
Location: include/linux/cpu.h:144
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8113c9ba)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff811824ff)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
```
```
In kernel/trace/ring_buffer.c (ffffffff811b8968)
Location: include/linux/cpu.h:144
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cc39d)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/events/hw_breakpoint.c (ffffffff81244c1f)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff8124a044)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:store_cpumask
```
```
In mm/vmstat.c (ffffffff82cf8cde)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
```
```
In mm/slab_common.c (ffffffff8127eec2)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (ffffffff812c03be)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff816e2629)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81993f85)
Location: include/linux/cpu.h:144
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81998243)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199a1e1)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199b580)
Location: include/linux/cpu.h:144
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8199f1fc)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff81a0d7d0)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c423)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff82fb4a92)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810582fa)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a310)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8109324e)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In kernel/workqueue.c (ffffffff810c6cbd)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810d43cc)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810dc107)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff8111099d)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_enter
```
```
In kernel/irq/affinity.c (ffffffff8112a4e5)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff81131f55)
Location: include/linux/cpu.h:145
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff811370ca)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f41f)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
```
```
In kernel/trace/ring_buffer.c (ffffffff811b63ac)
Location: include/linux/cpu.h:145
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811c99f8)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/events/hw_breakpoint.c (ffffffff8124f26f)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81253cf4)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:store_cpumask
```
```
In mm/vmstat.c (ffffffff82fe59b6)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
```
```
In mm/slab_common.c (ffffffff812879c8)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (ffffffff812cbe0e)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff817002bf)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819972e5)
Location: include/linux/cpu.h:145
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199b363)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199d341)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199e620)
Location: include/linux/cpu.h:145
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a198c)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff81a0481c)
Location: include/linux/cpu.h:145
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ce2c)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff831bf003)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058c4a)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff831cdc47)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093c4e)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In kernel/workqueue.c (ffffffff810c8462)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810d600c)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810de127)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff8111136c)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/irq/affinity.c (ffffffff8112a765)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff811326e5)
Location: include/linux/cpu.h:150
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81137d9a)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff8117fa5f)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
```
```
In kernel/trace/ring_buffer.c (ffffffff811b64fc)
Location: include/linux/cpu.h:150
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cadda)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/events/hw_breakpoint.c (ffffffff81253b7f)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81258384)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff831effbf)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
```
```
In mm/swap_slots.c (ffffffff812d29be)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff816e1e83)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197e62e)
Location: include/linux/cpu.h:150
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81980043)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81981e81)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff819831fa)
Location: include/linux/cpu.h:150
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8198696c)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff819ec035)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
</details>
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
In kernel/workqueue.c (ffff800010121af0)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffff80001012f564)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffff800010138840)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffff800010170788)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/irq/affinity.c (ffff800010188508)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffff80001018c4ec)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffff8000101e3538)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
```
In kernel/trace/ring_buffer.c (ffff800010219b34)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffff800010231f78)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffff8000102a3f24)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffff8000102a9164)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffff8000114534fc)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffff8000102e79b4)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (ffff800010329b4c)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffff8000107a2e80)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b24230)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/core/dev.c (ffff800010bcbc00)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0375544)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (c037f170)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (c03875b0)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (c03bb700)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (c03d6e68)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (c03dd718)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/cgroup/cpuset.c (c0424000)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
```
In kernel/trace/ring_buffer.c (c0457f4c)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/trace/trace_hwlat.c (c046d5c8)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (c04d3600)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (c04d8530)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (c152e180)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (c050ba58)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (c0540424)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c0bfe2a4)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/core/dev.c (c0ce9bb0)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/rtasd.c (c000000000040e10)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c7a8c)
Location: include/linux/cpu.h:138
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dff3c)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_core_pmu_counters
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c0000000001210b0)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvm_hv_vm_deactivated
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvm_hv_vm_activated
```
```
In kernel/workqueue.c (c00000000016b310)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (c000000000178948)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (c00000000018459c)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (c0000000001c9050)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (c0000000001e2588)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (c0000000001ead38)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/livepatch/transition.c (c0000000001f3074)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (c000000000254154)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
```
In kernel/trace/ring_buffer.c (c00000000029bb3c)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc414)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (c000000000356450)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (c00000000035e148)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (c00000000137b934)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (c0000000003a980c)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (c0000000004006ec)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c18ad0)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1ca78)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn
```
```
In net/core/dev.c (c000000000ca852c)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In kernel/workqueue.c (0)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffe000178c02)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpu.h:138
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/cpu.h:138
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpu.h:138
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/cpu.h:138
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpu.h:138
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c213)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff82890a51)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105401a)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810561b3)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba9a)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810be0b2)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810c9a1c)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810d25ca)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/irq/affinity.c (ffffffff8111a8b5)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff8111f04d)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff811265c0)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff81168c45)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
```
In kernel/trace/ring_buffer.c (ffffffff81198888)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811abf61)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff8121158f)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81216054)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828c375d)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff81248f15)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (ffffffff81285ee1)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff8160516d)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a8e3)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186cbc5)
Location: include/linux/cpu.h:138
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186e5dc)
Location: include/linux/cpu.h:138
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818704a7)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff818ceda9)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100aa43)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff8288e960)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810440ea)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810463c3)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a5ba)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810ac8e2)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810b823c)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810c0bfe)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810f29fe)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (ffffffff8110b925)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff81110a5d)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81119020)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff8115be55)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
```
In kernel/trace/ring_buffer.c (ffffffff8118bd98)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119ee51)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120431f)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81208db4)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828bbe82)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff8123bec5)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (ffffffff81277d51)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff815f021d)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81833593)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835815)
Location: include/linux/cpu.h:138
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8183659c)
Location: include/linux/cpu.h:138
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81839a27)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff81888ec9)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c1d3)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff828a3a51)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105444a)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810565e3)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba4a)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810bd612)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810c8f4c)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810d037a)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810ff7d0)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/affinity.c (ffffffff811187a5)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff8111cf3d)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff811244b0)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff81166a15)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
```
In kernel/trace/ring_buffer.c (ffffffff81196658)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a9d31)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120f32f)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81213df4)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828d64dd)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff81246cb5)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (ffffffff81283cf1)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff81629c5d)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bb673)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bd955)
Location: include/linux/cpu.h:138
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818bf36c)
Location: include/linux/cpu.h:138
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c1d57)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff8191fda9)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c403)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff828a3a65)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810558ca)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057b33)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ddaa)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810c5992)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
```
```
In kernel/smpboot.c (ffffffff810d14bc)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810d9cc9)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff8110aad4)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/affinity.c (ffffffff81123e35)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff8112a4dd)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81130b0f)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff81174095)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
```
```
In kernel/trace/ring_buffer.c (ffffffff811a4268)
Location: include/linux/cpu.h:138
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b7b71)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff8121e23f)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81223034)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828db8fe)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff812564e5)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (ffffffff812939e1)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff81643afd)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d7963)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9c65)
Location: include/linux/cpu.h:138
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818db67c)
Location: include/linux/cpu.h:138
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818de067)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff81941b09)
Location: include/linux/cpu.h:138
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
</ul>
