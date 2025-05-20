# Function: <code>alloc_cpumask_var</code>

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
In arch/x86/xen/mmu.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/cpuset.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In net/core/flow.c (0)
Location: include/linux/cpumask.h:669
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:669
Inline: True
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
In arch/x86/xen/mmu.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/cpuset.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In net/core/flow.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:671
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8144b627)
Location: lib/cpumask.c:93
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:alloc_sched_domains
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/sched/core.c:SyS_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:compat_SyS_sched_getaffinity
  - kernel/compat.c:compat_SyS_sched_setaffinity
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:alloc_trial_cpuset
  - kernel/cpuset.c:alloc_trial_cpuset
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/flow.c:flow_cache_flush
  - net/core/net-sysfs.c:store_xps_map
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8144b610-ffffffff8144b620: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff818ebce7)
Location: lib/cpumask.c:125
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/sched/core.c:SyS_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:compat_SyS_sched_getaffinity
  - kernel/compat.c:compat_SyS_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/flow.c:flow_cache_flush
  - net/core/net-sysfs.c:store_xps_map
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff818ebcd0-ffffffff818ebce0: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81971cc7)
Location: lib/cpumask.c:142
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/sched/core.c:SyS_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:compat_SyS_sched_getaffinity
  - kernel/compat.c:compat_SyS_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81971cb0-ffffffff81971cc0: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff819ce070)
Location: lib/cpumask.c:143
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff819ce060-ffffffff819ce070: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a07530)
Location: lib/cpumask.c:143
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81a07520-ffffffff81a07530: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a76e90)
Location: lib/cpumask.c:144
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81a76e80-ffffffff81a76e90: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81aae390)
Location: lib/cpumask.c:144
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81aae380-ffffffff81aae390: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815e80b0)
Location: lib/cpumask.c:144
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff815e80a0-ffffffff815e80b0: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8160d210)
Location: lib/cpumask.c:144
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8160d200-ffffffff8160d210: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815f06b0)
Location: lib/cpumask.c:144
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/profile.c:profile_init
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff815f06a0-ffffffff815f06b0: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8165d790)
Location: lib/cpumask.c:144
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/profile.c:profile_init
  - kernel/compat.c:__x64_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__x64_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - fs/io-wq.c:io_wq_create
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8165d780-ffffffff8165d790: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81776cf0)
Location: lib/cpumask.c:144
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/build_utility.c:alloc_sched_domains
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/profile.c:profile_init
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - io_uring/io-wq.c:io_wq_create
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81776cd0-ffffffff81776cea: alloc_cpumask_var (STB_GLOBAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff81038f16)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp_pv.c (ffffffff83e7187b)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff83e7f6dd)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108954e)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108b988)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e1c1)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e8997a)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e858)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a95af)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d3867)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff83ea47c2)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/cpu.c (ffffffff83ea54b5)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/cpu.c:alloc_frozen_cpus
```
```
In kernel/workqueue.c (ffffffff81117d9b)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff811406f2)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff83ea8927)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/build_policy.c (ffffffff81160e21)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_init
```
```
In kernel/sched/build_utility.c (ffffffff8116dc8a)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:alloc_sched_domains
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:cpupri_init
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
```
```
In kernel/irq/irqdesc.c (ffffffff83eab1e4)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/manage.c (ffffffff81196e1e)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/irq/proc.c (ffffffff811a1c6b)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff811a66df)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff811d197b)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/hrtimer.c (ffffffff811d9f66)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/tick-broadcast.c (ffffffff83eae865)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/compat.c (ffffffff81202ac2)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
```
In kernel/cgroup/cpuset.c (ffffffff8121dd70)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/taskstats.c (ffffffff8124ef8c)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/ring_buffer.c (ffffffff8125e6dc)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81269a53)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_boot.c (ffffffff83eb6f7d)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In kernel/events/core.c (ffffffff83eb93ec)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In kernel/padata.c (ffffffff813547c1)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In io_uring/io_uring.c (ffffffff81788eb4)
Location: include/linux/cpumask.h:840
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817a79f4)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/cpu_rmap.c (ffffffff818912bf)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff818e663e)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/acpi/acpi_processor.c (ffffffff8196595c)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d655b)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff819d7fae)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a13e85)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/base/cpu.c (ffffffff81af02b6)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
```
In drivers/base/power/domain.c (ffffffff81b0c1ca)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/node.c (ffffffff81b14874)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83efed3a)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2dda8)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d337d7)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d36b99)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3906a)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81d3bd63)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff81dba2e0)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81dc21d9)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In net/core/net-sysfs.c (ffffffff81e0d957)
Location: include/linux/cpumask.h:840
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/xen/mmu_pv.c (ffffffff81038e46)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp_pv.c (ffffffff83692751)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8369ddb5)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff836a242d)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089b43)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108e8d8)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81091071)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/smpboot.c (ffffffff836ad036)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b20f8)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810acee9)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6c47)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff836c8b42)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/cpu.c (ffffffff836c9885)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/cpu.c:alloc_frozen_cpus
```
```
In kernel/workqueue.c (ffffffff81124fbb)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff8114c5b2)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff836cd373)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/build_policy.c (ffffffff81171571)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_init
```
```
In kernel/sched/build_utility.c (ffffffff8117e250)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:alloc_sched_domains
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/irq/irqdesc.c (ffffffff836d01a4)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/manage.c (ffffffff811a88dc)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/irq/proc.c (ffffffff811b3901)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/profile.c (ffffffff811e5c11)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/hrtimer.c (ffffffff811ee456)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/tick-broadcast.c (ffffffff836d3825)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/compat.c (ffffffff81217e82)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
```
In kernel/cgroup/cpuset.c (ffffffff81233e70)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/taskstats.c (ffffffff81266345)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/ring_buffer.c (ffffffff812758bc)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81280be2)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_osnoise.c (ffffffff81297633)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
```
```
In kernel/trace/trace_boot.c (ffffffff836dc519)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In kernel/events/core.c (ffffffff836dea1c)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In kernel/padata.c (ffffffff81385af9)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In io_uring/io_uring.c (ffffffff817cad91)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_iowq_aff
```
```
In io_uring/io-wq.c (ffffffff817e8877)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/cpu_rmap.c (ffffffff818d35cf)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/group_cpus.c (ffffffff818e70f1)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:group_cpus_evenly
```
```
In drivers/pci/pci-driver.c (ffffffff81929c7e)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/acpi/acpi_processor.c (ffffffff819abebc)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1de9b)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a1f9b2)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a5ced5)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/base/cpu.c (ffffffff81b3e416)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
```
In drivers/base/power/domain.c (ffffffff81b5a20a)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/node.c (ffffffff81b635e4)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/net/virtio_net.c (ffffffff81c4cdbe)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83724bb2)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d97018)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9cb67)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9ff46)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da3b0a)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81da68c3)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff81e2abc6)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81e31739)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In net/core/net-sysfs.c (ffffffff81e80ba7)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/xen/mmu_pv.c (ffffffff8103f2f6)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp_pv.c (ffffffff838c229f)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff838cd975)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff838d252d)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090c5c)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81095c68)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098431)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/smpboot.c (ffffffff838dd527)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e25b8)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b3b09)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df477)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff838f97a0)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/cpu.c (ffffffff838fa4d5)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/cpu.c:alloc_frozen_cpus
```
```
In kernel/workqueue.c (ffffffff838fbcbf)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/workqueue.c:init_pod_type
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_unbound_exclude_cpumask
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff81158272)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff838fe781)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/build_policy.c (ffffffff8117ee81)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_init
```
```
In kernel/sched/build_utility.c (ffffffff8118fb9e)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:alloc_sched_domains
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/irq/irqdesc.c (ffffffff839015c4)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/manage.c (ffffffff811b843c)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/irq/proc.c (ffffffff811c3781)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/rcu/tree.c (ffffffff83903bce)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/profile.c (ffffffff811fb961)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/hrtimer.c (ffffffff812045d6)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/tick-broadcast.c (ffffffff839055e5)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/compat.c (ffffffff8122fa42)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
```
In kernel/cgroup/cpuset.c (ffffffff8124dac0)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/taskstats.c (ffffffff81280235)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/ring_buffer.c (ffffffff8129011c)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff8129ae06)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b2c83)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
```
```
In kernel/trace/trace_boot.c (ffffffff8390eb49)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In kernel/events/core.c (ffffffff8391105c)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In kernel/padata.c (ffffffff813aefb8)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In io_uring/register.c (ffffffff8182b361)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - io_uring/register.c:io_register_iowq_aff
```
```
In io_uring/io-wq.c (ffffffff8182e5f7)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/cpu_rmap.c (ffffffff819256af)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/group_cpus.c (ffffffff8192e111)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:group_cpus_evenly
```
```
In drivers/pci/pci-driver.c (ffffffff8197247e)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/acpi/acpi_processor.c (ffffffff819f628b)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a691ab)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a6acd2)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/pmdomain/core.c (ffffffff81aa1c04)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:pm_genpd_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81aaee75)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/base/cpu.c (ffffffff81b960a6)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
```
In drivers/base/node.c (ffffffff81bb70f4)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/net/virtio_net.c (ffffffff81d0265e)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83958a22)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4eca7)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e54827)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e57dc5)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5bb9a)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81e5e953)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff81ee89d6)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81eefeb9)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In net/core/net-sysfs.c (ffffffff81f41b67)
Location: include/linux/cpumask.h:912
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:show_rps_map
```
</details>
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
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/pci/controller/pci-xgene-msi.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/pci/controller/pcie-iproc-msi.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/base/arch_topology.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:756
Inline: True
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
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/base/arch_topology.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:756
Inline: True
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
In arch/powerpc/kernel/rtas.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In arch/powerpc/platforms/powernv/subcore.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In arch/powerpc/platforms/pseries/suspend.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:756
Inline: True
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
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:756
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:756
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
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a4d1e0)
Location: lib/cpumask.c:144
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81a4d1d0-ffffffff81a4d1e0: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a0a310)
Location: lib/cpumask.c:144
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/hv/channel_mgmt.c:init_vp_index
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81a0a300-ffffffff81a0a310: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ab95d0)
Location: lib/cpumask.c:144
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81ab95c0-ffffffff81ab95d0: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool alloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ac5a20)
Location: lib/cpumask.c:144
Inline: True
Inline callers:
  - lib/cpumask.c:zalloc_cpumask_var
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/cpu.c:alloc_frozen_cpus
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/topology.c:alloc_sched_domains
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/proc.c:default_affinity_write
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81ac5a10-ffffffff81ac5a20: alloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
