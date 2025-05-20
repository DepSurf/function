# Function: <code>set_bits</code>

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
In <code>5.13</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c00000000001898c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:user_enable_block_step
  - arch/powerpc/kernel/ptrace.c:user_enable_single_step
```
```
In arch/powerpc/kernel/signal_32.c (c00000000001f15c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
```
```
In arch/powerpc/kernel/process.c (c000000000020ee8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:start_thread
```
```
In arch/powerpc/kernel/cacheinfo.c (c00000000002acc4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
```
```
In arch/powerpc/kernel/setup-common.c (c00000000134a30c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/kernel/signal_64.c (c000000000034224)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
```
```
In arch/powerpc/kernel/watchdog.c (c000000000036d68)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:start_watchdog
```
```
In arch/powerpc/kernel/fadump.c (c00000000004d4e0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kernel/fadump.c:fadump_setup_cpu_notes_buf
```
```
In arch/powerpc/kernel/iommu.c (c000000000051230)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_table_reserve_pages
  - arch/powerpc/kernel/iommu.c:iommu_table_reserve_pages
```
```
In arch/powerpc/kernel/smp.c (c000000000055fd0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:set_cpus_related
  - arch/powerpc/kernel/smp.c:set_cpus_related
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
```
```
In arch/powerpc/kernel/pci-common.c (c00000000006d01c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller
```
```
In arch/powerpc/kernel/crash.c (c000000000070728)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kernel/crash.c:crash_ipi_callback
```
```
In arch/powerpc/mm/pgtable.c (c000000000087e88)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:set_pte_at
```
```
In arch/powerpc/mm/mmu_context.c (c00000000008a108)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/mm/mmu_context.c:switch_mm_irqs_off
```
```
In arch/powerpc/mm/drmem.c (c00000000008a2cc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008d034)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000095e64)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:exit_flush_lazy_tlbs
```
```
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0ea4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_free
```
```
In arch/powerpc/mm/numa.c (c0000000000a35d8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/mm/numa.c:map_cpu_to_node
  - arch/powerpc/mm/numa.c:node_set_online
```
```
In arch/powerpc/lib/sstep.c (c0000000000b1b9c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/lib/sstep.c:emulate_loadstore
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000be4c0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target
```
```
In arch/powerpc/sysdev/xive/spapr.c (c0000000000c0afc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_get_ipi
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c74d0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
```
```
In arch/powerpc/platforms/powernv/opal-flash.c (c0000000000ca14c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-flash.c:image_data_write
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c0000000000ccdb0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_unmask
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d3864)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_reserve_m64_pe
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfde0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In arch/powerpc/platforms/pseries/reconfig.c (c0000000000eccbc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
```
```
In arch/powerpc/platforms/pseries/dlpar.c (c0000000000f3094)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_parse_cc_node
```
```
In arch/powerpc/platforms/pseries/smp.c (c00000000136392c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/smp.c:smp_init_pseries
  - arch/powerpc/platforms/pseries/smp.c:smp_pSeries_kick_cpu
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9fa8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fc508)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In arch/powerpc/xmon/xmon.c (c000000000110fdc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:xmon_core
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c0000000001202b4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_rm_h_page_init
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_rm_h_page_init
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c000000000121538)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_confer
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c000000000122f04)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_deliver_irq
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_set_vcpu_irq
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012a2f8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_online
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline
```
```
In kernel/fork.c (c00000000013a2bc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (c00000000013c700)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/panic.c:__warn
```
```
In kernel/cpu.c (c000000001365f0c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/exit.c (c0000000001440fc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (c00000000014ed90)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (c000000000153d1c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sys.c (c000000000161974)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_compat_sys_times
  - kernel/sys.c:__se_sys_times
```
```
In kernel/workqueue.c (c000000001367020)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/kthread.c (c0000000001731d0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/sched/core.c (c00000000018c2a4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (c00000000018e808)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (c00000000019ed38)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (c0000000001a1588)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (c0000000001a6088)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In kernel/sched/cpupri.c (c0000000001ae1d8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (c0000000001aea9c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (c0000000001b0b40)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (c00000000136b4e4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/manage.c (c0000000001d5fe8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/resend.c (c0000000001d81f8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/chip.c (c0000000001da274)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/generic-chip.c (c0000000001dbce4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In kernel/irq/affinity.c (c0000000001e2014)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (c0000000001e66f8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (c0000000001f3468)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In kernel/profile.c (c0000000001f84cc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/time.c (c0000000001fb0ac)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/time/time.c:__se_sys_time32
  - kernel/time/time.c:__se_sys_time
```
```
In kernel/time/tick-broadcast.c (c00000000021928c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/time/tick-sched.c (c00000000021b7e8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_oneshot_notify
  - kernel/time/tick-sched.c:tick_clock_notify
```
```
In kernel/module.c (c00000000022c168)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
```
In kernel/kexec_core.c (c000000000230eb0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/cgroup/cgroup.c (c0000000002440d8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a72c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (c00000000024b0bc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (c000000001370d78)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_flag
```
```
In kernel/auditsc.c (c000000000265bd8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (c000000000287128)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (c00000000028d2f4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ring_buffer.c (c0000000002a0ae0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (c0000000002ada08)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc464)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_events.c (c0000000002c87a0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (c0000000002ccc44)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d29f0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
```
In kernel/bpf/cgroup.c (c00000000033aaf8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (c000000000353a00)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/ring_buffer.c (c000000000354f5c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (c000000000355e70)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (c00000000035c060)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_dup_mmap
  - kernel/events/uprobes.c:uprobe_dup_mmap
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:uprobe_munmap
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In kernel/rseq.c (c00000000036063c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/rseq.c:__se_sys_rseq
```
```
In mm/filemap.c (c000000000366f6c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In mm/oom_kill.c (c00000000036f8d4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/maccess.c (c000000000371f98)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page-writeback.c (c000000000372f1c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
  - mm/page-writeback.c:__writepage
```
```
In mm/readahead.c (c000000000378268)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (c00000000037c0f4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (c00000000037f404)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
```
```
In mm/vmscan.c (c00000000038a220)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c000000000395670)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/vmstat.c (c00000000137b8f8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/backing-dev.c (c00000000039f260)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/percpu.c (c00000000137bfb0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/workingset.c (c0000000003b4d7c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/gup.c (c0000000003b787c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (c0000000003ce770)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/rmap.c (c0000000003d9928)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (c0000000003ee0e0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/shuffle.c (c000000000eecdd8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/page_io.c (c0000000003f5c98)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:swap_slot_free_notify
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (c0000000003f8094)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (c0000000003fae30)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (c0000000004013fc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/zswap.c (c0000000004041bc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (c000000000410904)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (c00000000041778c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/ksm.c (c00000000041f8bc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (c000000000422dd4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:get_map
```
```
In mm/memory_hotplug.c (c00000000042da9c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (c000000000439bf8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c00000000043b970)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (c000000000449118)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (c00000000045b404)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:memcg_set_shrinker_bit
```
```
In mm/memory-failure.c (c000000000461294)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In mm/zsmalloc.c (c000000000465be4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
  - mm/zsmalloc.c:create_page_chain
```
```
In mm/userfaultfd.c (c00000000046ab94)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c00000000046c918)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/read_write.c (c000000000477be4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (c00000000048532c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/fcntl.c (c000000000496ed0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/libfs.c (c0000000004bf20c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/fs-writeback.c (c0000000004ccce0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/splice.c (c0000000004d1f78)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (c0000000004dc840)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:attach_nobh_buffers
  - fs/buffer.c:attach_nobh_buffers
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:mark_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/block_dev.c (c0000000004e5edc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/mpage.c (c0000000004ec7b4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (c000000000508130)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (c00000000050ef5c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/dax.c (c000000000514e98)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/crypto/crypto.c (c000000000517ea0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/crypto/bio.c (c00000000051e630)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (c00000000052195c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (c00000000052ffc4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (c000000000533bdc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/iomap/buffered-io.c (c00000000053a8a4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/quota/dquot.c (c000000000542a40)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_acquire
  - fs/quota/dquot.c:dquot_acquire
```
```
In fs/proc/base.c (c000000000554810)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/proc/proc_sysctl.c (c000000000561f60)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/balloc.c (c00000000057d560)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (c00000000057fe20)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ext4_jbd2.c (c0000000005811c0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (c000000000583b1c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (c0000000005973b8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (c000000000599ea0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (c0000000005a082c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (c0000000005b0910)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (c0000000005b24b4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (c0000000005bd100)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/migrate.c (c0000000005c26e4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (c0000000005c42c0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (c0000000005cd4c0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/page-io.c (c0000000005d13e0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (c0000000005d1e60)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (c0000000005d35c0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (c0000000005ee178)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (c0000000005ff540)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/verity.c (c00000000060101c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/jbd2/transaction.c (c000000000606080)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c000000000607174)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (c000000000609ae8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (c00000000060bbf0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (c000000000613c50)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (c0000000006170d8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (c0000000006198c4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (c00000000061a03c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ramfs/inode.c (c00000000061cb68)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In fs/hugetlbfs/inode.c (c00000000061d090)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In fs/fat/dir.c (c0000000006224f8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (c00000000062651c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/fat/inode.c (c0000000006299c0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In fs/ecryptfs/mmap.c (c0000000006371ac)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (c000000000637620)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c00000000064a5c0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:request_wait_answer
```
```
In fs/fuse/dir.c (c00000000064bca0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (c0000000006559fc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (c00000000065d268)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/fuse/readdir.c:parse_dirplusfile
```
```
In ipc/shm.c (c0000000006736c4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - ipc/shm.c:__se_compat_sys_shmat
  - ipc/shm.c:__se_sys_shmat
```
```
In security/keys/gc.c (c000000000679a00)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (c00000000067a820)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/request_key.c (c000000000683d38)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:cache_requested_key
```
```
In security/tomoyo/common.c (c0000000006e2e1c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/integrity/iint.c (c00000000072aefc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In security/integrity/ima/ima_main.c (c00000000072dd48)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (c0000000007378ac)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In block/blk-core.c (c000000000774278)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
```
```
In block/blk-mq.c (c000000000789c9c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - block/blk-mq.c:blk_mq_hctx_mark_pending
```
```
In block/blk-mq-sched.c (c00000000078f0c0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/blk-cgroup.c (c0000000007ab770)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In block/blk-zoned.c (c0000000007bf560)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/bitmap.c (c0000000007ce5dc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/cpu_rmap.c (c000000000816a58)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/irq_poll.c (c00000000081cf90)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (c00000000081ec84)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/gpio/gpiolib.c (c000000000841f98)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-legacy.c (c000000000843f5c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
```
```
In drivers/gpio/gpiolib-sysfs.c (c000000000847674)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/core.c (c00000000084ea9c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/bus.c (c000000000854dc8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (c00000000088a094)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f7f4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_map_addr
```
```
In drivers/pci/controller/pcie-xilinx.c (c000000000891bdc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
```
```
In drivers/rapidio/rio.c (c00000000089555c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008ae02c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/dma/dmaengine.c (c0000000008c8474)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/regulator/core.c (c0000000008e2698)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
```
In drivers/tty/tty_io.c (c0000000008f138c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/n_tty.c (c0000000008f4608)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_receive_char_special
```
```
In drivers/tty/tty_ioctl.c (c0000000008fa854)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/tty_ldisc.c (c0000000008fb538)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
```
In drivers/tty/tty_port.c (c0000000008fe5e0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/tty_jobctrl.c (c0000000008ff424)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/tty/pty.c (c000000000900558)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_set_lock
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/pty.c:pty_close
  - drivers/tty/pty.c:pty_close
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/sysrq.c (c000000000903a4c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/keyboard.c (c00000000090c040)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/serial/serial_core.c (c00000000092a19c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/8250/8250_dma.c (c000000000934278)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/max310x.c (0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/tty/serdev/serdev-ttyport.c (c000000000941f34)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
```
```
In drivers/char/mem.c (c00000000094262c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/misc.c (c00000000094adb0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/frontend.c (c000000000953cd0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agpioc_acquire_wrap
  - drivers/char/agp/frontend.c:agpioc_acquire_wrap
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_open
  - drivers/char/agp/frontend.c:agp_controller_make_current
  - drivers/char/agp/frontend.c:agp_controller_make_current
```
```
In drivers/char/agp/generic.c (c000000000956830)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_get_key
```
```
In drivers/char/agp/compat_ioctl.c (c000000000957dfc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/base/core.c (c00000000097bde8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/base/cacheinfo.c (c00000000098e92c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/base/power/domain.c (c0000000009a6e18)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (c0000000009bd8e4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/nvdimm/bus.c (c0000000009fe2c8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a01bb0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0b30c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
```
```
In drivers/nvdimm/label.c (c000000000a11b88)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/nvdimm/security.c (c000000000a18008)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
```
In drivers/dax/super.c (c000000000a18f04)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:run_dax
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1dab0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/scsi/scsi_error.c (c000000000a2b16c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_sysfs.c (c000000000a39b5c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/ata/libata-scsi.c (c000000000a682b4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/net/tun.c (c000000000a9f79c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aaa7ac)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/usb/core/hub.c (c000000000ad1c84)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (c000000000ad68f4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (c000000000ae7dd8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (c000000000ae9968)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:claimintf
```
```
In drivers/usb/core/port.c (c000000000af3eac)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/dwc2/hcd.c (c000000000b02f54)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
```
In drivers/usb/host/ehci-hcd.c (c0000000013b1414)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ohci-hcd.c (c0000000013b1650)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (c0000000013b17d0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (c000000000b4685c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
```
```
In drivers/usb/host/xhci-ring.c (c000000000b56a48)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (c000000000b60d2c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/input/mousedev.c (c000000000b7c6e4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (c000000000b81e60)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
```
```
In drivers/input/misc/uinput.c (c000000000b8649c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
```
In drivers/media/cec/cec-core.c (c000000000b9ee28)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (c000000000bb04e4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/thermal/thermal_core.c (c000000000bbb488)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc77b4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_write
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
```
```
In drivers/md/md.c (c000000000bd6c94)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_wakeup_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:consistency_policy_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (c000000000be76c8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_write_all
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (c000000000bec780)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_lock_for_deletion
  - drivers/md/dm.c:dm_lock_for_deletion
```
```
In drivers/md/dm-io.c (c000000000bfb9a8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In drivers/md/dm-kcopyd.c (c000000000bfdb04)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/opp/cpu.c (c000000000c0cf98)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/opp/of.c (c000000000c0d564)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (c000000000c154fc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1bdf4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_cpu_init
```
```
In drivers/cpuidle/cpuidle-pseries.c (c000000000c22414)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
```
```
In drivers/cpuidle/cpuidle-powernv.c (c000000000c22a74)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
```
```
In drivers/leds/led-core.c (c000000000c3d74c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/of/base.c (c000000000c43840)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_get_alias_list
```
```
In drivers/of/platform.c (c000000000c486a4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_create
```
```
In drivers/of/dynamic.c (c000000000c4c184)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_prop_dup
  - drivers/of/dynamic.c:__of_detach_node
```
```
In drivers/of/fdt.c (c000000000c4e56c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/of/fdt.c:__unflatten_device_tree
```
```
In drivers/of/irq.c (c0000000013bc520)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_init
```
```
In drivers/of/overlay.c (c000000000c56d8c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/of/overlay.c:dup_and_fixup_symbol_prop
```
```
In net/socket.c (c000000000c76478)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/sock.c (c000000000c80d78)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/datagram.c (c000000000c946d4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (c000000000c96704)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/sysctl_net_core.c (c000000000ca0600)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (c000000000ca1de0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/core/dev.c:init_dummy_netdev
  - net/core/dev.c:init_dummy_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_alloc_name_ns
```
```
In net/core/neighbour.c (c000000000cc2664)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (c000000000cf524c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:show_rps_map
```
```
In net/core/skmsg.c (c000000000cfa610)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/gro_cells.c (c000000000d29c24)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In net/sched/sch_generic.c (c000000000d330d0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/genetlink.c (c000000000d512a0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
```
In net/ipv4/tcp.c (c000000000d7c0bc)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_output.c (c000000000d8d4b0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
```
```
In net/ipv4/arp.c (c000000000db5310)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (c000000000dbf0ec)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/ipmr.c (c000000000de78e8)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/tcp_bpf.c (c000000000df3768)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (c000000000e15a38)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_accept
```
```
In net/ipv6/addrconf.c (c000000000e27ee4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
```
In net/ipv6/ndisc.c (c000000000e522e0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/dns_resolver/dns_key.c (c0000000013c7f80)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
```
In net/dns_resolver/dns_query.c (c000000000eb22f4)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/dns_resolver/dns_query.c:dns_query
```
```
In net/ncsi/ncsi-rsp.c (c000000000eb5904)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/ncsi/ncsi-manage.c (c000000000eba3c0)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In lib/vsprintf.c (c000000000edbb2c)
Location: arch/powerpc/include/asm/bitops.h:84
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
</details>
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
