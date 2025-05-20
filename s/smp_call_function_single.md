# Function: <code>smp_call_function_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81103930)
Location: kernel/smp.c:271
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_notifier
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/intel_cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback
  - arch/x86/kernel/kvm.c:kvm_cpu_notify
  - arch/x86/kernel/kvm.c:kvm_cpu_notify
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:synchronize_sched_expedited
  - kernel/rcu/tree.c:rcu_cpu_notify
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_many
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:task_function_call
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:perf_ioctl
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/idle/intel_idle.c:cpu_hotplug_notify
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81103930-ffffffff81103a59: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8110ad60)
Location: kernel/smp.c:255
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_online
  - arch/x86/kernel/cpu/intel_cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback
  - arch/x86/kernel/kvm.c:kvm_cpu_notify
  - arch/x86/kernel/kvm.c:kvm_cpu_notify
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/idle/intel_idle.c:cpu_hotplug_notify
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff8110ad60-ffffffff8110ae82: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81112580)
Location: kernel/smp.c:259
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_online
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/kernel/cpu/intel_cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81112580-ffffffff811126a2: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81113af0)
Location: kernel/smp.c:268
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_online
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/intel_cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81113af0-ffffffff81113bd0: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8111f080)
Location: kernel/smp.c:268
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_online
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/intel_cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sched/membarrier.c:SyS_membarrier
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff8111f080-ffffffff8111f17c: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8112c3c0)
Location: kernel/smp.c:268
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_online
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff8112c3c0-ffffffff8112c4ac: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81137c90)
Location: kernel/smp.c:268
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81137c90-ffffffff81137d7c: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81142df0)
Location: kernel/smp.c:269
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81142df0-ffffffff81142ef1: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114e930)
Location: kernel/smp.c:269
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff8114e930-ffffffff8114ea31: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115f440)
Location: kernel/smp.c:337
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/rcu/tree.c:sync_sched_exp_online_cleanup
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff8115f440-ffffffff8115f55e: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115b3e0)
Location: kernel/smp.c:467
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/rcu/tree.c:sync_sched_exp_online_cleanup
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
```
**Symbols:**

```
ffffffff8115b3e0-ffffffff8115b4fe: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115cac0)
Location: kernel/smp.c:709
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
```
**Symbols:**

```
ffffffff8115cac0-ffffffff8115cbd7: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81181ca0)
Location: kernel/smp.c:709
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
```
**Symbols:**

```
ffffffff81181ca0-ffffffff81181db7: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811b83c0)
Location: kernel/smp.c:728
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
```
**Symbols:**

```
ffffffff811b83c0-ffffffff811b84f8: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811f96f0)
Location: kernel/smp.c:727
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:hybrid_get_cpu_scaling
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
```
**Symbols:**

```
ffffffff811f96f0-ffffffff811f9841: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8120ed90)
Location: kernel/smp.c:581
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:hwp_get_cpu_scaling
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
```
**Symbols:**

```
ffffffff8120ed90-ffffffff8120eee1: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81226530)
Location: kernel/smp.c:601
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/time/hrtimer.c:hrtimers_cpu_dying
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:hwp_get_cpu_scaling
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
```
**Symbols:**

```
ffffffff81226530-ffffffff81226681: smp_call_function_single (STB_GLOBAL)
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
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffff8000101bcf00)
Location: kernel/smp.c:269
Inline: False
Direct callers:
  - arch/arm64/kernel/cacheinfo.c:populate_cache_leaves
  - arch/arm64/kernel/cacheinfo.c:init_cache_level
  - virt/kvm/kvm_main.c:kvm_init
  - virt/kvm/arm/arm.c:kvm_arch_init
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - drivers/soc/fsl/qbman/qman.c:qman_delete_cgr_safe
```
**Symbols:**

```
ffff8000101bcf00-ffff8000101bd0bc: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c0404d88)
Location: kernel/smp.c:269
Inline: False
Direct callers:
  - arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
```
**Symbols:**

```
c0404d88-c0404fdc: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c000000000222e30)
Location: kernel/smp.c:269
Inline: False
Direct callers:
  - arch/powerpc/kernel/sysfs.c:store_tsr3
  - arch/powerpc/kernel/sysfs.c:show_tsr3
  - arch/powerpc/kernel/sysfs.c:store_tsr2
  - arch/powerpc/kernel/sysfs.c:show_tsr2
  - arch/powerpc/kernel/sysfs.c:store_tsr1
  - arch/powerpc/kernel/sysfs.c:show_tsr1
  - arch/powerpc/kernel/sysfs.c:store_tsr0
  - arch/powerpc/kernel/sysfs.c:show_tsr0
  - arch/powerpc/kernel/sysfs.c:store_siar
  - arch/powerpc/kernel/sysfs.c:show_siar
  - arch/powerpc/kernel/sysfs.c:store_sier
  - arch/powerpc/kernel/sysfs.c:show_sier
  - arch/powerpc/kernel/sysfs.c:store_ier
  - arch/powerpc/kernel/sysfs.c:show_ier
  - arch/powerpc/kernel/sysfs.c:store_ber
  - arch/powerpc/kernel/sysfs.c:show_ber
  - arch/powerpc/kernel/sysfs.c:store_mer
  - arch/powerpc/kernel/sysfs.c:show_mer
  - arch/powerpc/kernel/sysfs.c:store_der
  - arch/powerpc/kernel/sysfs.c:show_der
  - arch/powerpc/kernel/sysfs.c:store_rpccr
  - arch/powerpc/kernel/sysfs.c:show_rpccr
  - arch/powerpc/kernel/sysfs.c:store_pccr
  - arch/powerpc/kernel/sysfs.c:show_pccr
  - arch/powerpc/kernel/sysfs.c:store_btcr
  - arch/powerpc/kernel/sysfs.c:show_btcr
  - arch/powerpc/kernel/sysfs.c:store_imaat
  - arch/powerpc/kernel/sysfs.c:show_imaat
  - arch/powerpc/kernel/sysfs.c:store_ima9
  - arch/powerpc/kernel/sysfs.c:show_ima9
  - arch/powerpc/kernel/sysfs.c:store_ima8
  - arch/powerpc/kernel/sysfs.c:show_ima8
  - arch/powerpc/kernel/sysfs.c:store_ima7
  - arch/powerpc/kernel/sysfs.c:show_ima7
  - arch/powerpc/kernel/sysfs.c:store_ima6
  - arch/powerpc/kernel/sysfs.c:show_ima6
  - arch/powerpc/kernel/sysfs.c:store_ima5
  - arch/powerpc/kernel/sysfs.c:show_ima5
  - arch/powerpc/kernel/sysfs.c:store_ima4
  - arch/powerpc/kernel/sysfs.c:show_ima4
  - arch/powerpc/kernel/sysfs.c:store_ima3
  - arch/powerpc/kernel/sysfs.c:show_ima3
  - arch/powerpc/kernel/sysfs.c:store_ima2
  - arch/powerpc/kernel/sysfs.c:show_ima2
  - arch/powerpc/kernel/sysfs.c:store_ima1
  - arch/powerpc/kernel/sysfs.c:show_ima1
  - arch/powerpc/kernel/sysfs.c:store_ima0
  - arch/powerpc/kernel/sysfs.c:show_ima0
  - arch/powerpc/kernel/sysfs.c:store_hid5
  - arch/powerpc/kernel/sysfs.c:show_hid5
  - arch/powerpc/kernel/sysfs.c:store_hid4
  - arch/powerpc/kernel/sysfs.c:show_hid4
  - arch/powerpc/kernel/sysfs.c:store_hid1
  - arch/powerpc/kernel/sysfs.c:show_hid1
  - arch/powerpc/kernel/sysfs.c:store_hid0
  - arch/powerpc/kernel/sysfs.c:show_hid0
  - arch/powerpc/kernel/sysfs.c:store_pa6t_pmc5
  - arch/powerpc/kernel/sysfs.c:show_pa6t_pmc5
  - arch/powerpc/kernel/sysfs.c:store_pa6t_pmc4
  - arch/powerpc/kernel/sysfs.c:show_pa6t_pmc4
  - arch/powerpc/kernel/sysfs.c:store_pa6t_pmc3
  - arch/powerpc/kernel/sysfs.c:show_pa6t_pmc3
  - arch/powerpc/kernel/sysfs.c:store_pa6t_pmc2
  - arch/powerpc/kernel/sysfs.c:show_pa6t_pmc2
  - arch/powerpc/kernel/sysfs.c:store_pa6t_pmc1
  - arch/powerpc/kernel/sysfs.c:show_pa6t_pmc1
  - arch/powerpc/kernel/sysfs.c:store_pa6t_pmc0
  - arch/powerpc/kernel/sysfs.c:show_pa6t_pmc0
  - arch/powerpc/kernel/sysfs.c:store_dscr
  - arch/powerpc/kernel/sysfs.c:show_dscr
  - arch/powerpc/kernel/sysfs.c:store_tscr
  - arch/powerpc/kernel/sysfs.c:show_tscr
  - arch/powerpc/kernel/sysfs.c:store_pir
  - arch/powerpc/kernel/sysfs.c:show_pir
  - arch/powerpc/kernel/sysfs.c:store_spurr
  - arch/powerpc/kernel/sysfs.c:show_spurr
  - arch/powerpc/kernel/sysfs.c:store_purr
  - arch/powerpc/kernel/sysfs.c:show_purr
  - arch/powerpc/kernel/sysfs.c:store_mmcra
  - arch/powerpc/kernel/sysfs.c:show_mmcra
  - arch/powerpc/kernel/sysfs.c:store_pmc8
  - arch/powerpc/kernel/sysfs.c:show_pmc8
  - arch/powerpc/kernel/sysfs.c:store_pmc7
  - arch/powerpc/kernel/sysfs.c:show_pmc7
  - arch/powerpc/kernel/sysfs.c:store_pmc6
  - arch/powerpc/kernel/sysfs.c:show_pmc6
  - arch/powerpc/kernel/sysfs.c:store_pmc5
  - arch/powerpc/kernel/sysfs.c:show_pmc5
  - arch/powerpc/kernel/sysfs.c:store_pmc4
  - arch/powerpc/kernel/sysfs.c:show_pmc4
  - arch/powerpc/kernel/sysfs.c:store_pmc3
  - arch/powerpc/kernel/sysfs.c:show_pmc3
  - arch/powerpc/kernel/sysfs.c:store_pmc2
  - arch/powerpc/kernel/sysfs.c:show_pmc2
  - arch/powerpc/kernel/sysfs.c:store_pmc1
  - arch/powerpc/kernel/sysfs.c:show_pmc1
  - arch/powerpc/kernel/sysfs.c:store_mmcr1
  - arch/powerpc/kernel/sysfs.c:show_mmcr1
  - arch/powerpc/kernel/sysfs.c:store_mmcr0
  - arch/powerpc/kernel/sysfs.c:show_mmcr0
  - arch/powerpc/kernel/watchdog.c:watchdog_nmi_start
  - arch/powerpc/kernel/watchdog.c:watchdog_nmi_stop
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_stop_cpu
```
**Symbols:**

```
c000000000222e30-c000000000222fe0: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffe0001405cc)
Location: kernel/smp.c:269
Inline: False
Direct callers:
  - arch/riscv/kernel/cacheinfo.c:populate_cache_leaves
  - arch/riscv/kernel/cacheinfo.c:init_cache_level
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
```
**Symbols:**

```
ffffffe0001405cc-ffffffe0001406e4: smp_call_function_single (STB_GLOBAL)
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
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81146f50)
Location: kernel/smp.c:269
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81146f50-ffffffff81147051: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8113a240)
Location: kernel/smp.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/hv/channel.c:vmbus_reset_channel_cb
  - drivers/hv/channel_mgmt.c:vmbus_add_channel_work
  - drivers/hv/channel_mgmt.c:vmbus_add_channel_work
  - drivers/hv/channel_mgmt.c:hv_process_channel_removal
```
**Symbols:**

```
ffffffff8113a240-ffffffff8113a33c: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81144e00)
Location: kernel/smp.c:269
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81144e00-ffffffff81144f01: smp_call_function_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81151980)
Location: kernel/smp.c:269
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
  - arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target
  - arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info
  - arch/x86/kernel/apic/vector.c:print_ICs
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:clockevents_unbind_device
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/relay.c:relay_late_setup_files
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_stop
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:task_function_call
  - arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsrl_on_cpu
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpu
  - arch/x86/lib/cache-smp.c:wbinvd_on_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/cpufreq/powernow-k8.c:powernowk8_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81151980-ffffffff81151aa7: smp_call_function_single (STB_GLOBAL)
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
