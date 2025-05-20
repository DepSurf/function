# Function: <code>variable__ffs</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100a5e1)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
```
In arch/x86/events/utils.c (ffffffff8100b3bc)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/utils.c:common_branch_type
```
```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff83e66195)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/events/intel/knc.c (ffffffff8101bc0a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/lbr.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81022735)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81025176)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e65d)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff83e6a3b5)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/suspend_hvm.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/topology.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064292)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81079743)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8107ceb0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff83e80136)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:print_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff83e81098)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e51e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/setup_percpu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/itmt.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810d530f)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/fork.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/softirq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/smpboot.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff81158b8f)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_task_rt
  - kernel/sched/build_policy.c:pick_task_rt
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
```
In kernel/sched/build_utility.c (ffffffff83ea917d)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sd_flags_show
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/power/poweroff.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/resend.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/generic-chip.c (ffffffff8119d7ee)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_get_irq_data
```
```
In kernel/irq/irq_sim.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811b5764)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
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
In kernel/livepatch/transition.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/module/main.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/profile.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/timer.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff811d92fc)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In kernel/time/clocksource.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff812101c6)
Location: arch/x86/include/asm/bitops.h:250
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
In kernel/cgroup/rstat.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/cgroup/rdma.c (ffffffff81216bb9)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/debug/gdbstub.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/watchdog.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/relay.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/taskstats.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/pid_list.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff8129d387)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
```
```
In kernel/trace/bpf_trace.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff812d5349)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/bpf/task_iter.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/memalloc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/events/core.c (ffffffff81337502)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
```
```
In kernel/events/callchain.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/oom_kill.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/page-writeback.c (ffffffff81366af3)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/readahead.c (ffffffff8136c417)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
```
```
In mm/swap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/vmscan.c (ffffffff813874e7)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
```
```
In mm/mmzone.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/percpu.c (ffffffff8139c3ed)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/compaction.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/list_lru.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/workingset.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/page_alloc.c (ffffffff83ec0397)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:split_free_page
```
```
In mm/memblock.c (ffffffff83ec1ef3)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff820c3184)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/swap_slots.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff820cafa4)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/kfence/core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/memory-failure.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/memfd.c (ffffffff814715dd)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dcache.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/inode.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/namespace.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/seq_file.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814c07d5)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff814d4aaf)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/dax.c (ffffffff814fa38c)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/locks.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/proc/stat.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/proc/uptime.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/proc/softirqs.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/ext4/super.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/ext4/sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In security/keys/keyring.c (ffffffff816500a5)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In security/selinux/ss/ebitmap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In security/selinux/ss/mls.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In security/landlock/fs.c (ffffffff816f277d)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_file_open
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
In crypto/scompress.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/bio.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-stat.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq-sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/genhd.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-iocost.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq-pci.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq-virtio.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq-rdma.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/random32.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/clz_ctz.c (ffffffff817d6ba0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff817d70ed)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - lib/find_bit.c:_find_next_zero_bit
  - lib/find_bit.c:_find_next_andnot_bit
  - lib/find_bit.c:_find_next_and_bit
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
  - lib/find_bit.c:_find_next_bit
  - lib/find_bit.c:_find_first_zero_bit
  - lib/find_bit.c:_find_first_and_bit
  - lib/find_bit.c:_find_first_bit
```
```
In lib/percpu-refcount.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/math/gcd.c (ffffffff817df39a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff817ea571)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/irq_poll.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/ubsan.c (ffffffff818a2171)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/pldmfw/pldmfw.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b3277)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff818cd0b2)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/pci-driver.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pci/search.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pci/setup-bus.c (ffffffff818f1660)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/pci/pcie/rcec.c (ffffffff818f7e7b)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff818fba6e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819270ff)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/idle/intel_idle.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/processor_core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/processor_thermal.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pnp/manager.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pnp/support.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pnp/interface.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff819fe59e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/dma/dmaengine.c (ffffffff81a049a6)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/xen/events/events_2l.c (ffffffff81a22ca0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a23b6b)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/regulator/irq_helpers.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/char/hpet.c (ffffffff81a9ae6a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_open
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab4ccb)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81aba421)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_pages
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_pages
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:first_pte_l7
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81abb6dc)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_unmap_pages
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_map_pages
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac2cf5)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap_pages
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81acfcd8)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_pgsize
  - drivers/iommu/iommu.c:iommu_pgsize
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad41f2)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff81ad8775)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81adaab8)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
```
In drivers/base/cacheinfo.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/base/node.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b3d1ea)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff81b4a2c9)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/nvdimm/core.c (ffffffff81b4ec38)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52bd1)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff81b8a82a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/ata/libata-sata.c (ffffffff81bbe15d)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/spi/spi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffffffff81bddde3)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c592fb)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c729e0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81c91858)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81c96b86)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff83efc412)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/input/input.c (ffffffff81ca7336)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/input/misc/uinput.c (ffffffff81cb79ba)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccd65a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdc2cf)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_genattrs
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/md/dm-stripe.c (ffffffff81d15f5c)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/amd-pstate.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/clocksource/hyperv_timer.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/devfreq/governor_passive.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/powercap/idle_inject.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/ras/ras.c (ffffffff81d89a66)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In net/core/sock.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/dev.c (ffffffff81dcf3c0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down_reason
```
```
In net/core/dst.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/neighbour.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/devlink.c (ffffffff81e400e4)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_reload_stats_update
```
```
In net/core/gro_cells.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/sched/act_api.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/route.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/proc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/xfrm/xfrm_proc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/route.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/proc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/mptcp/mib.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/mctp/route.c (ffffffff82013d51)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
```
```
In arch/x86/power/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/radix-tree.c (ffffffff8203b3df)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/vsprintf.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/xarray.c (ffffffff820483fa)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
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
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
```
```
In arch/x86/events/utils.c (ffffffff8100ab8c)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/utils.c:common_branch_type
```
```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff83686805)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/events/intel/knc.c (ffffffff8101b8db)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/lbr.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81022425)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81025066)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e63d)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8368ad45)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/suspend_hvm.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/topology.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065bde)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107b9f3)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8107f260)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff836a4523)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810913ce)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/setup_percpu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b6402)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810d87ff)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/fork.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/softirq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/smpboot.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff81168e6f)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_task_rt
  - kernel/sched/build_policy.c:pick_task_rt
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
```
In kernel/sched/build_utility.c (ffffffff836cdc62)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sd_flags_show
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/power/poweroff.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/generic-chip.c (ffffffff811af69e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_get_irq_data
```
```
In kernel/irq/irq_sim.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811c66f4)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
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
In kernel/livepatch/transition.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/module/main.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/profile.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/timer.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff811ed75c)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In kernel/time/clocksource.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81225bd6)
Location: arch/x86/include/asm/bitops.h:250
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
In kernel/cgroup/rstat.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/cgroup/rdma.c (ffffffff8122c4a7)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/debug/gdbstub.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/watchdog.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/watchdog_perf.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/relay.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/taskstats.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/pid_list.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff812baed0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
```
```
In kernel/trace/bpf_trace.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8130c73e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:mark_precise_scalar_ids
  - kernel/bpf/verifier.c:mark_precise_scalar_ids
```
```
In kernel/bpf/task_iter.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/memalloc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/bpf/cpumask.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/events/core.c (ffffffff81367d06)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
```
```
In kernel/events/callchain.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/oom_kill.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/page-writeback.c (ffffffff8139914b)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/readahead.c (ffffffff8139e637)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
```
```
In mm/swap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/vmscan.c (ffffffff813b0d99)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/mmzone.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/mm_init.c (ffffffff836e27c7)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/mm_init.c:node_map_pfn_alignment
```
```
In mm/percpu.c (ffffffff813cf4cf)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/compaction.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/show_mem.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/list_lru.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/workingset.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/page_alloc.c (ffffffff8141c3cd)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/page_alloc.c:split_free_page
```
```
In mm/memblock.c (ffffffff836e6895)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/memblock.c:free_low_memory_core_early
```
```
In mm/memory_hotplug.c (ffffffff82146f30)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/swap_slots.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8214f13b)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/kfence/core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/memory-failure.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/memfd.c (ffffffff814a5ac6)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/dcache.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/inode.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/namespace.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/seq_file.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814f5911)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff8150c58a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
```
```
In fs/dax.c (ffffffff815317dd)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/locks.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/proc/stat.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/proc/uptime.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/proc/softirqs.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/ext4/super.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/ext4/sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In security/keys/keyring.c (ffffffff81688985)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In security/selinux/ss/ebitmap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In security/selinux/ss/mls.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In security/landlock/fs.c (ffffffff8172cbab)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_mknod
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
In crypto/scompress.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/bio.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-stat.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq-sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/genhd.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-iocost.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq-pci.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In block/blk-mq-virtio.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/random32.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/clz_ctz.c (ffffffff81815bb0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff818161ba)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - lib/find_bit.c:_find_next_zero_bit
  - lib/find_bit.c:_find_next_or_bit
  - lib/find_bit.c:_find_next_andnot_bit
  - lib/find_bit.c:_find_next_and_bit
  - lib/find_bit.c:__find_nth_and_andnot_bit
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
  - lib/find_bit.c:_find_next_bit
  - lib/find_bit.c:_find_first_zero_bit
  - lib/find_bit.c:_find_first_and_bit
  - lib/find_bit.c:_find_first_bit
```
```
In lib/percpu-refcount.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/math/gcd.c (ffffffff8181eb7a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff8182a6ed)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/irq_poll.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/ubsan.c (ffffffff818e45a1)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/group_cpus.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/pldmfw/pldmfw.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f62c7)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81910112)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/pci-driver.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pci/search.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pci/setup-bus.c (ffffffff81934a8e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/pci/pcie/rcec.c (ffffffff8193b2db)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff8193f33e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196b2d1)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/idle/intel_idle.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/processor_core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/processor_thermal.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pnp/manager.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pnp/support.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/pnp/interface.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff81a4725e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/dma/dmaengine.c (ffffffff81a4d806)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/xen/events/events_2l.c (ffffffff81a6bf4e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6d02b)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/regulator/irq_helpers.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/char/hpet.c (ffffffff81ae66fa)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_open
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b012cb)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b069e1)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_pages
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_pages
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:first_pte_l7
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b07a04)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_unmap_pages
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_map_pages
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0fb95)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap_pages
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/iommu/intel/perfmon.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81b1ef88)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_pgsize
  - drivers/iommu/iommu.c:iommu_pgsize
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b229c2)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff81b26895)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b28d68)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
```
In drivers/base/cacheinfo.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/base/node.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b9067a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9d73f)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/nvdimm/core.c (ffffffff81ba2088)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6081)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff81bde7ba)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/ata/libata-sata.c (ffffffff81c159c9)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/spi/spi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/phy/phy-c45.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc02fb)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd9fd0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81cf7f68)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81cfd946)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff83722212)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/input/input.c (ffffffff81d0e516)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/input/misc/uinput.c (ffffffff81d1f06a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d353ef)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In drivers/hwmon/hwmon.c (ffffffff81d447af)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_genattrs
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/md/dm-stripe.c (ffffffff81d7f1b9)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/amd-pstate.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/firmware/efi/unaccepted_memory.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/clocksource/hyperv_timer.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/devfreq/governor_passive.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/powercap/idle_inject.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/ras/ras.c (ffffffff81df8066)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In net/core/sock.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/dev.c (ffffffff81e3fff0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down_reason
```
```
In net/core/dst.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/neighbour.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/page_pool.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/core/gro_cells.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/sched/act_api.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/route.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/proc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/xfrm/xfrm_proc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/route.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/proc.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/devlink/leftover.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/devlink/dev.c (ffffffff820444b4)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/devlink/dev.c:__devlink_reload_stats_update
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/mptcp/mib.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/mctp/route.c (ffffffff82090bfd)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
```
```
In arch/x86/power/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/radix-tree.c (ffffffff820b98bf)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/vsprintf.c (0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In lib/xarray.c (ffffffff820c6bbc)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
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
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
```
```
In arch/x86/events/utils.c (ffffffff8101030c)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/events/utils.c:common_branch_type
```
```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff838b66db)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/events/intel/knc.c (ffffffff8102145b)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/lbr.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81027d85)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102b1c6)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810347ad)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff838ba905)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/xen/suspend_hvm.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106d045)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81086d70)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff838d45a3)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810987ab)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/cpu/debugfs.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/setup_percpu.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e6d12)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810e107f)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/fork.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/softirq.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/smpboot.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff811761bf)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_task_rt
  - kernel/sched/build_policy.c:pick_task_rt
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
```
In kernel/sched/build_utility.c (ffffffff838ff0a3)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sd_flags_show
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/power/poweroff.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/irq/generic-chip.c (ffffffff811bf1ce)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_get_irq_data
```
```
In kernel/irq/irq_sim.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811da44e)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/livepatch/transition.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/module/main.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/profile.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/time/timer.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81203abc)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In kernel/time/clocksource.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/crash_core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8123d866)
Location: arch/x86/include/asm/bitops.h:249
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
In kernel/cgroup/rstat.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/cgroup/rdma.c (ffffffff81244536)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/debug/gdbstub.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/watchdog.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/watchdog_perf.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/relay.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/taskstats.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/pid_list.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff812d7520)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
```
```
In kernel/trace/bpf_trace.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff81328a3f)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:mark_precise_scalar_ids
  - kernel/bpf/verifier.c:mark_precise_scalar_ids
```
```
In kernel/bpf/map_iter.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/task_iter.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/memalloc.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/bpf/cpumask.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/events/core.c (ffffffff81390c26)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
```
```
In kernel/events/callchain.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/filemap.c (ffffffff813bac40)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/oom_kill.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/page-writeback.c (ffffffff813c2f4b)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/readahead.c (ffffffff813c82d5)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
```
```
In mm/swap.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/vmscan.c (ffffffff813da112)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/shrinker.c (ffffffff813e49a0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - mm/shrinker.c:shrink_slab_memcg
```
```
In mm/mmzone.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/mm_init.c (ffffffff839150c7)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - mm/mm_init.c:node_map_pfn_alignment
```
```
In mm/percpu.c (ffffffff813f9fcf)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/compaction.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/show_mem.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/list_lru.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/page_alloc.c (ffffffff81448e8d)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - mm/page_alloc.c:split_free_page
```
```
In mm/memblock.c (ffffffff83919d4e)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff822296ae)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/swap_slots.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/zswap.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8223200b)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
```
```
In mm/kfence/core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/memory-failure.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In mm/memfd.c (ffffffff814d6a76)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/dcache.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/inode.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/namespace.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/seq_file.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8152a01e)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/dax.c (ffffffff815666bd)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/locks.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/proc/stat.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/proc/uptime.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/proc/softirqs.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/ext4/super.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/ext4/sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In security/keys/keyring.c (ffffffff816c4e05)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In security/selinux/ss/ebitmap.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In security/selinux/ss/mls.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In security/landlock/fs.c (ffffffff8176d723)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:is_eacces
```
```
In crypto/scompress.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In block/bio.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In block/blk-mq.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In block/blk-stat.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In block/blk-mq-sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In block/genhd.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In block/blk-iocost.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In block/blk-mq-pci.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In block/blk-mq-virtio.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/random32.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/clz_ctz.c (ffffffff8185ac90)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff8185b2fa)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - lib/find_bit.c:_find_next_zero_bit
  - lib/find_bit.c:_find_next_or_bit
  - lib/find_bit.c:_find_next_andnot_bit
  - lib/find_bit.c:_find_next_and_bit
  - lib/find_bit.c:__find_nth_and_andnot_bit
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
  - lib/find_bit.c:_find_next_bit
  - lib/find_bit.c:_find_first_zero_bit
  - lib/find_bit.c:_find_first_and_bit
  - lib/find_bit.c:_find_first_bit
```
```
In lib/percpu-refcount.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/bitmap-str.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/math/gcd.c (ffffffff818649ea)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff8187c15d)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/irq_poll.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/ubsan.c (ffffffff8192b5a1)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/group_cpus.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/pldmfw/pldmfw.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193d0b1)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81957fe2)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/pci-driver.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/pci/search.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/pci/setup-bus.c (ffffffff8197d7d9)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/pci/pcie/rcec.c (ffffffff8198416b)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff819880de)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4db1)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/idle/intel_idle.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/acpi/processor_core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/acpi/processor_thermal.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/pnp/manager.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/pnp/support.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/pnp/interface.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff81a92cfe)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/dma/dmaengine.c (ffffffff81a994a6)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/pmdomain/core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/pmdomain/governor.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/xen/events/events_2l.c (ffffffff81abe006)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abf0ef)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/regulator/irq_helpers.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/char/hpet.c (ffffffff81b39a8a)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_open
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b56787)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5a92f)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_read_and_clear_dirty
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_pages
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_pages
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:first_pte_l7
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5ba34)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_unmap_pages
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_map_pages
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b64485)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap_pages
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/iommu/intel/perfmon.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/iommu/iommufd/iova_bitmap.c (ffffffff81b720a7)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_alloc
```
```
In drivers/iommu/iommu.c (ffffffff81b75428)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_pgsize
  - drivers/iommu/iommu.c:iommu_pgsize
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79492)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff81b7d4d5)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b7fd0b)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
```
In drivers/base/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/base/node.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be45ea)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf172f)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/nvdimm/core.c (ffffffff81bf6218)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa301)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff81c33695)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/ata/libata-sata.c (ffffffff81c6ab9e)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/gpu/drm/drm_print.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/net/phy/phy-c45.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d750bb)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8f00f)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81dad898)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81db32a6)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff83956042)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/input/input.c (ffffffff81dc4166)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/input/misc/uinput.c (ffffffff81dd4d9a)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb57f)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfb65d)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/md/dm-stripe.c (ffffffff81e367d9)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/cpufreq/amd-pstate.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/firmware/efi/unaccepted_memory.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/clocksource/hyperv_timer.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/devfreq/governor_passive.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/powercap/idle_inject.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In drivers/ras/ras.c (ffffffff81eae776)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In net/core/sock.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/core/dev.c (ffffffff81efe950)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down_reason
```
```
In net/core/dst.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/core/neighbour.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/core/page_pool.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/core/gro_cells.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/sched/act_api.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv4/route.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv4/proc.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv4/tcp_sigpool.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/xfrm/xfrm_proc.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv6/route.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv6/proc.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/devlink/dev.c (ffffffff821033b4)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - net/devlink/dev.c:__devlink_reload_stats_update
```
```
In net/devlink/trap.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/mptcp/mib.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In net/mctp/route.c (ffffffff8216713d)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
```
```
In arch/x86/power/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/radix-tree.c (ffffffff821941cf)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/vsprintf.c (0)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
```
```
In lib/xarray.c (ffffffff821a153c)
Location: arch/x86/include/asm/bitops.h:249
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
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
