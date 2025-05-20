# Function: <code>get_online_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void get_online_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081150)
Location: kernel/cpu.c:93
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
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
  - kernel/watchdog.c:lockup_detector_suspend
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_set_cpumasks
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_add_cpu
  - kernel/padata.c:padata_remove_cpu
  - mm/swap.c:lru_add_drain_all
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_cpuup_callback
  - mm/slab_common.c:kmem_cache_shrink
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
ffffffff81081150-ffffffff81081191: get_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void get_online_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810836d0)
Location: kernel/cpu.c:170
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
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
  - kernel/watchdog.c:lockup_detector_suspend
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/net/virtio_net.c:virtnet_set_channels
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - net/core/flow.c:flow_cache_flush
```
**Symbols:**

```
ffffffff810836d0-ffffffff81083711: get_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void get_online_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81088120)
Location: kernel/cpu.c:236
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
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
  - kernel/watchdog.c:lockup_detector_suspend
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - net/core/dev.c:rollback_registered_many
  - net/core/flow.c:flow_cache_flush
```
**Symbols:**

```
ffffffff81088120-ffffffff81088161: get_online_cpus (STB_GLOBAL)
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
In arch/x86/events/intel/core.c (ffffffff8100acc8)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e53d)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff820a303c)
Location: include/linux/cpu.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042d5e)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104ceaf)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ed9b)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810781d7)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810a171d)
Location: include/linux/cpu.h:126
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
In kernel/smpboot.c (ffffffff810a9ad5)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
```
In kernel/sched/core.c (ffffffff810af5d6)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810d8c46)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (ffffffff810efd9e)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff810f4571)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/livepatch/transition.c (ffffffff810f8ed6)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff8112defc)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/watchdog.c (ffffffff8114f4a1)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:lockup_detector_suspend
```
```
In kernel/trace/ring_buffer.c (ffffffff8115e2b8)
Location: include/linux/cpu.h:126
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff81170974)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff811afbf8)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff811b3f4c)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/swap.c (ffffffff811cc809)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/vmstat.c (ffffffff820d095b)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff811e61cd)
Location: include/linux/cpu.h:126
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
In mm/swap_slots.c (ffffffff811ec787)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In mm/memcontrol.c (ffffffff8123cec3)
Location: include/linux/cpu.h:126
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81530e94)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81765fd5)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817683fc)
Location: include/linux/cpu.h:126
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81769657)
Location: include/linux/cpu.h:126
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176c3aa)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff817ca4cd)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/flow.c (ffffffff817ef05b)
Location: include/linux/cpu.h:126
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
In arch/x86/events/intel/core.c (ffffffff8100b288)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff826a9330)
Location: include/linux/cpu.h:124
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8105079f)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052709)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107e533)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810a7f7d)
Location: include/linux/cpu.h:124
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
In kernel/smpboot.c (ffffffff810b01dd)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
```
In kernel/sched/core.c (ffffffff810b68b6)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810e0fc7)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (ffffffff810f894e)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff810fe447)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/livepatch/transition.c (ffffffff8110391f)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff8113aa8c)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ring_buffer.c (ffffffff8116b268)
Location: include/linux/cpu.h:124
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff8117db46)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff811c3783)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff811c7bdc)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/swap.c (ffffffff811e1829)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/vmstat.c (ffffffff826d9392)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff811fc40d)
Location: include/linux/cpu.h:124
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
In mm/swap_slots.c (ffffffff81202af7)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff81591e9c)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817dbfb5)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817de2ec)
Location: include/linux/cpu.h:124
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817df3f7)
Location: include/linux/cpu.h:124
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e220a)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff81843fc1)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f9aea)
Location: include/linux/cpu.h:124
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
In arch/x86/events/intel/core.c (ffffffff8100b99c)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff826d24b1)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810533ef)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105541d)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810815a3)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810aeb2d)
Location: include/linux/cpu.h:128
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
In kernel/smpboot.c (ffffffff810b6fe5)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
```
In kernel/sched/core.c (ffffffff810bc4f7)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810e9548)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (ffffffff81100ecb)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff8110536f)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/livepatch/transition.c (ffffffff8110be88)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff81149a65)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ring_buffer.c (ffffffff8117a39f)
Location: include/linux/cpu.h:128
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff8118c98f)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff811e3a5d)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff811e7e1c)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff8270383c)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff8121d565)
Location: include/linux/cpu.h:128
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
In mm/swap_slots.c (ffffffff8124ea57)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff815c9224)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81824c65)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81826fb5)
Location: include/linux/cpu.h:128
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818293bb)
Location: include/linux/cpu.h:128
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182afd5)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff81897f00)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/xfrm/xfrm_policy.c (ffffffff8195055a)
Location: include/linux/cpu.h:128
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
In arch/x86/events/intel/core.c (ffffffff8100ba5c)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff828887c1)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81050a6f)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052abd)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810881b3)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810b7c8d)
Location: include/linux/cpu.h:130
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
In kernel/smpboot.c (ffffffff810c0465)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810c4cd7)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810f4b68)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (ffffffff8110c7df)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff81110ba1)
Location: include/linux/cpu.h:130
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81117678)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff81155755)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ring_buffer.c (ffffffff8118736f)
Location: include/linux/cpu.h:130
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119a49f)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff811f3f2d)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff811f8dec)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828baf65)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff81230555)
Location: include/linux/cpu.h:130
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
In mm/swap_slots.c (ffffffff81262f37)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff815e27f4)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81850bf5)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81852eb5)
Location: include/linux/cpu.h:130
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81853deb)
Location: include/linux/cpu.h:130
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81856f45)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff818ba242)
Location: include/linux/cpu.h:130
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
In arch/x86/events/intel/core.c (ffffffff8100bdeb)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff8289f93a)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053b2f)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055c6b)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108be01)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810bd71d)
Location: include/linux/cpu.h:132
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
In kernel/smpboot.c (ffffffff810c6565)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810ce36b)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810fce3a)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/affinity.c (ffffffff81115ee2)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff8111a5fa)
Location: include/linux/cpu.h:132
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8112193b)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff8116301c)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ring_buffer.c (ffffffff81194764)
Location: include/linux/cpu.h:132
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a8107)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120bc0a)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81210b3c)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828d23c6)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff81240565)
Location: include/linux/cpu.h:132
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
In mm/swap_slots.c (ffffffff8127dea7)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff81614385)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8189412d)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81896475)
Location: include/linux/cpu.h:132
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818978c7)
Location: include/linux/cpu.h:132
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8189a695)
Location: include/linux/cpu.h:132
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff818fc6f4)
Location: include/linux/cpu.h:132
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
In arch/x86/events/intel/core.c (ffffffff8100c1fb)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff828a2a0c)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105441f)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810565ab)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ca71)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810c3cfd)
Location: include/linux/cpu.h:137
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
In kernel/smpboot.c (ffffffff810cf645)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810d7f6b)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff811092a6)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/affinity.c (ffffffff811222c2)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff811269fa)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8112df5b)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff811705a5)
Location: include/linux/cpu.h:137
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
In kernel/trace/ring_buffer.c (ffffffff811a0224)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b3907)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff81218eea)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff8121d9f4)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828da838)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff81250857)
Location: include/linux/cpu.h:137
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
In mm/swap_slots.c (ffffffff8128d8f7)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff81635875)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c614d)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c8485)
Location: include/linux/cpu.h:137
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c9e67)
Location: include/linux/cpu.h:137
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818cc845)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff8192ed22)
Location: include/linux/cpu.h:137
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
In arch/x86/events/intel/core.c (ffffffff8100d3ab)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff82cc8c36)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810594af)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b81e)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093c99)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In kernel/workqueue.c (ffffffff810cb9df)
Location: include/linux/cpu.h:143
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
In kernel/smpboot.c (ffffffff810d91d5)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810df27b)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff81113c9c)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_enter
```
```
In kernel/irq/affinity.c (ffffffff8112e8e2)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff81136638)
Location: include/linux/cpu.h:143
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8113c93b)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff811824dd)
Location: include/linux/cpu.h:143
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
In kernel/trace/ring_buffer.c (ffffffff811b88c2)
Location: include/linux/cpu.h:143
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cc378)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/events/hw_breakpoint.c (ffffffff81244bca)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff8124a034)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:store_cpumask
```
```
In mm/vmstat.c (ffffffff82cf8c6d)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
```
```
In mm/slab_common.c (ffffffff8127eeab)
Location: include/linux/cpu.h:143
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
In mm/swap_slots.c (ffffffff812c038d)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff816e2525)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81993f1d)
Location: include/linux/cpu.h:143
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff819981cd)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199a1d1)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199b618)
Location: include/linux/cpu.h:143
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8199f195)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff81a0d749)
Location: include/linux/cpu.h:143
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
In arch/x86/events/intel/core.c (ffffffff8100c40b)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff82fb4a4d)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105827f)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a26e)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810931e9)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In kernel/workqueue.c (ffffffff810c6c3f)
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
In kernel/smpboot.c (ffffffff810d4375)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810dbf1b)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff8111093f)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_enter
```
```
In kernel/irq/affinity.c (ffffffff8112a4d2)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff81131ea8)
Location: include/linux/cpu.h:144
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8113704b)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f3fd)
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
In kernel/trace/ring_buffer.c (ffffffff811b6322)
Location: include/linux/cpu.h:144
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811c99d3)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/events/hw_breakpoint.c (ffffffff8124f21a)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81253ce4)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:store_cpumask
```
```
In mm/vmstat.c (ffffffff82fe5945)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
```
```
In mm/slab_common.c (ffffffff812879a5)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/swap_slots.c (ffffffff812cbddd)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff81700195)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8199727d)
Location: include/linux/cpu.h:144
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199b2ed)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199d331)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199e6b8)
Location: include/linux/cpu.h:144
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a1925)
Location: include/linux/cpu.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff81a046ef)
Location: include/linux/cpu.h:144
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
In arch/x86/events/intel/core.c (ffffffff8100ce0b)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff831befbe)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058bcf)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff831cdc12)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093be9)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In kernel/workqueue.c (ffffffff810c840d)
Location: include/linux/cpu.h:149
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
In kernel/smpboot.c (ffffffff810d5fb5)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810ddf3b)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff81111312)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/irq/affinity.c (ffffffff8112a752)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff81132638)
Location: include/linux/cpu.h:149
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81137d1b)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff8117fa3d)
Location: include/linux/cpu.h:149
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
In kernel/trace/ring_buffer.c (ffffffff811b64b9)
Location: include/linux/cpu.h:149
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cadb5)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/events/hw_breakpoint.c (ffffffff81253b2a)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81258374)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff831eff4b)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:all_vm_events
```
```
In mm/swap_slots.c (ffffffff812d298d)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff816e1d95)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197e5c6)
Location: include/linux/cpu.h:149
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8197ffcd)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81981e71)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff819831a5)
Location: include/linux/cpu.h:149
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81986905)
Location: include/linux/cpu.h:149
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff819ebeff)
Location: include/linux/cpu.h:149
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
In kernel/workqueue.c (ffff800010121aa0)
Location: include/linux/cpu.h:137
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
In kernel/smpboot.c (ffff80001012f524)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffff800010138684)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffff800010170728)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/irq/affinity.c (ffff8000101884f0)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffff80001018c460)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffff8000101e34c8)
Location: include/linux/cpu.h:137
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
In kernel/trace/ring_buffer.c (ffff800010219b10)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffff800010231f3c)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffff8000102a3eac)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffff8000102a9154)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffff80001145345c)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffff8000102e794c)
Location: include/linux/cpu.h:137
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
In mm/swap_slots.c (ffff800010329b44)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffff8000107a2d38)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b24190)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/core/dev.c (ffff800010bcbb64)
Location: include/linux/cpu.h:137
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
In kernel/workqueue.c (c03754fc)
Location: include/linux/cpu.h:137
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
In kernel/smpboot.c (c037f12c)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (c038734c)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (c03bb6a4)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (c03d6e4c)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (c03dd664)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/cgroup/cpuset.c (c0423f24)
Location: include/linux/cpu.h:137
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
In kernel/trace/ring_buffer.c (c0457f00)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/trace/trace_hwlat.c (c046d5a0)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (c04d3590)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (c04d8520)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (c152e174)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (c050ba4c)
Location: include/linux/cpu.h:137
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
In mm/swap_slots.c (c054041c)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c0bfe200)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/core/dev.c (c0ce9b08)
Location: include/linux/cpu.h:137
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
In arch/powerpc/kernel/rtasd.c (c000000000040d9c)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c7a4c)
Location: include/linux/cpu.h:137
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfeac)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_core_pmu_counters
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c00000000012108c)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvm_hv_vm_deactivated
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvm_hv_vm_activated
```
```
In kernel/workqueue.c (c00000000016b2bc)
Location: include/linux/cpu.h:137
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
In kernel/smpboot.c (c0000000001788d4)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (c000000000184348)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (c0000000001c8fd8)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (c0000000001e2560)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (c0000000001eac60)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/livepatch/transition.c (c0000000001f2fa4)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (c0000000002540b8)
Location: include/linux/cpu.h:137
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
In kernel/trace/ring_buffer.c (c00000000029baec)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc3d8)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (c0000000003563c4)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (c00000000035e134)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (c00000000137b858)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (c0000000003a9780)
Location: include/linux/cpu.h:137
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
In mm/swap_slots.c (c0000000004006e0)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c189ec)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1c8f0)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn
```
```
In net/core/dev.c (c000000000ca844c)
Location: include/linux/cpu.h:137
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
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpu.h:137
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/cpu.h:137
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpu.h:137
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/cpu.h:137
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpu.h:137
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
In arch/x86/events/intel/core.c (ffffffff8100c1fb)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff82890a0c)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053f9f)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105612b)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba31)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810be06d)
Location: include/linux/cpu.h:137
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
In kernel/smpboot.c (ffffffff810c99c5)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810d243b)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/irq/affinity.c (ffffffff8111a8a2)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff8111efda)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8112653b)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff81168bc5)
Location: include/linux/cpu.h:137
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
In kernel/trace/ring_buffer.c (ffffffff81198844)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811abf27)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff8121153a)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81216044)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828c36ec)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff81248ea7)
Location: include/linux/cpu.h:137
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
In mm/swap_slots.c (ffffffff81285ed7)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff81605065)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a86d)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186cba5)
Location: include/linux/cpu.h:137
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186e587)
Location: include/linux/cpu.h:137
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81870445)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff818ced22)
Location: include/linux/cpu.h:137
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
In arch/x86/events/intel/core.c (ffffffff8100aa2b)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff8288e91b)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8104406f)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104633b)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a551)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810ac89d)
Location: include/linux/cpu.h:137
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
In kernel/smpboot.c (ffffffff810b81e5)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810c0a7b)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810f29a4)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/affinity.c (ffffffff8110b912)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff811109ea)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81118f9b)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff8115bdd5)
Location: include/linux/cpu.h:137
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
In kernel/trace/ring_buffer.c (ffffffff8118bd54)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119ee17)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff812042ca)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81208da4)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828bbe11)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff8123be57)
Location: include/linux/cpu.h:137
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
In mm/swap_slots.c (ffffffff81277d47)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff815f0115)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8183351d)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818357f5)
Location: include/linux/cpu.h:137
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81836547)
Location: include/linux/cpu.h:137
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818399c5)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff81888e42)
Location: include/linux/cpu.h:137
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
In arch/x86/events/intel/core.c (ffffffff8100c1bb)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff828a3a0c)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810543cf)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105655b)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b9e1)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810bd5cd)
Location: include/linux/cpu.h:137
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
In kernel/smpboot.c (ffffffff810c8ef5)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810d01eb)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff810ff776)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/affinity.c (ffffffff81118792)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff8111ceca)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8112442b)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff81166995)
Location: include/linux/cpu.h:137
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
In kernel/trace/ring_buffer.c (ffffffff81196614)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a9cf7)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120f2da)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81213de4)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828d646c)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff81246c47)
Location: include/linux/cpu.h:137
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
In mm/swap_slots.c (ffffffff81283ce7)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff81629b55)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bb5fd)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bd935)
Location: include/linux/cpu.h:137
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818bf317)
Location: include/linux/cpu.h:137
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c1cf5)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff8191fd22)
Location: include/linux/cpu.h:137
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
In arch/x86/events/intel/core.c (ffffffff8100c3eb)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/events/intel/pt.c (ffffffff828a3a20)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105584f)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057aab)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108dd41)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810c594d)
Location: include/linux/cpu.h:137
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
In kernel/smpboot.c (ffffffff810d1465)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_unregister_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810d9b67)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/power/suspend.c (ffffffff8110aa7a)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/affinity.c (ffffffff81123e22)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff8112a46a)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81130a90)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/cgroup/cpuset.c (ffffffff81174015)
Location: include/linux/cpu.h:137
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
In kernel/trace/ring_buffer.c (ffffffff811a4224)
Location: include/linux/cpu.h:137
Inline: True
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b7b37)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff8121e1ea)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
```
In kernel/padata.c (ffffffff81223024)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/vmstat.c (ffffffff828db88d)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_start
```
```
In mm/slab_common.c (ffffffff81256477)
Location: include/linux/cpu.h:137
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
In mm/swap_slots.c (ffffffff812939d7)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
```
In drivers/acpi/processor_idle.c (ffffffff816439f5)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d78ed)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9c45)
Location: include/linux/cpu.h:137
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818db627)
Location: include/linux/cpu.h:137
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818de005)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
```
```
In net/core/dev.c (ffffffff81941a82)
Location: include/linux/cpu.h:137
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
