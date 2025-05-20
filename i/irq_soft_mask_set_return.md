# Function: <code>irq_soft_mask_set_return</code>

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
In init/main.c (c0000000013444a0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/powerpc/kernel/process.c (c000000000021ac8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:__switch_to
```
```
In arch/powerpc/kernel/time.c (c00000000002bc28)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:arch_irq_work_raise
```
```
In arch/powerpc/kernel/traps.c (c00000000002c884)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:oops_begin
```
```
In arch/powerpc/kernel/setup-common.c (c00000000002fc8c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:ppc_panic_event
```
```
In arch/powerpc/kernel/setup_64.c (c000000000031170)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup_64.c:panic_smp_self_stop
```
```
In arch/powerpc/kernel/nvram_64.c (c000000000035d90)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/nvram_64.c:oops_to_nvram
```
```
In arch/powerpc/kernel/watchdog.c (c000000000037494)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:stop_watchdog
  - arch/powerpc/kernel/watchdog.c:stop_watchdog
  - arch/powerpc/kernel/watchdog.c:stop_watchdog
  - arch/powerpc/kernel/watchdog.c:stop_watchdog
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
```
```
In arch/powerpc/kernel/mce_power.c (c00000000003a3cc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/mce_power.c:addr_to_pfn
```
```
In arch/powerpc/kernel/rtas.c (c00000000003f52c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:rtas_give_timebase
  - arch/powerpc/kernel/rtas.c:rtas_give_timebase
  - arch/powerpc/kernel/rtas.c:__se_sys_rtas
  - arch/powerpc/kernel/rtas.c:rtas_call
```
```
In arch/powerpc/kernel/smp.c (c0000000000563a4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:smp_prepare_boot_cpu
  - arch/powerpc/kernel/smp.c:nmi_ipi_lock_start
  - arch/powerpc/kernel/smp.c:nmi_ipi_lock_start
  - arch/powerpc/kernel/smp.c:nmi_ipi_lock_start
  - arch/powerpc/kernel/smp.c:nmi_ipi_lock_start
```
```
In arch/powerpc/kernel/crash.c (c000000000070da0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/crash.c:default_machine_crash_shutdown
  - arch/powerpc/kernel/crash.c:crash_kexec_secondary
  - arch/powerpc/kernel/crash.c:crash_ipi_callback
```
```
In arch/powerpc/kernel/machine_kexec_64.c (c000000000071738)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec
  - arch/powerpc/kernel/machine_kexec_64.c:kexec_smp_down
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008dda0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:update_mmu_cache
```
```
In arch/powerpc/mm/book3s64/slb.c (c00000000008f4f0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/slb.c:switch_slb
  - arch/powerpc/mm/book3s64/slb.c:preload_new_slb_context
  - arch/powerpc/mm/book3s64/slb.c:slb_setup_new_exec
  - arch/powerpc/mm/book3s64/slb.c:slb_flush_and_restore_bolted
```
```
In arch/powerpc/mm/book3s64/hash_tlb.c (c000000000091e68)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_tlb.c:flush_tlb_pmd_range
  - arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range
```
```
In arch/powerpc/mm/book3s64/hash_native.c (c0000000000924ac)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_invalidate
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000096510)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb
```
```
In arch/powerpc/mm/slice.c (c0000000000a3d24)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In arch/powerpc/platforms/powernv/setup.c (c0000000000c1d7c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-call.c (c0000000000c222c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-call.c:opal_call
```
```
In arch/powerpc/platforms/powernv/smp.c (c0000000000cdec0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_cpu_kill_self
```
```
In arch/powerpc/platforms/pseries/lpar.c (c0000000000eb4d0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:__trace_hcall_exit
  - arch/powerpc/platforms/pseries/lpar.c:__trace_hcall_entry
```
```
In arch/powerpc/platforms/pseries/iommu.c (c0000000000f0128)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9e34)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_mach_cpu_die
```
```
In arch/powerpc/xmon/xmon.c (c000000000111438)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:xmon_irq
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011d730)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
```
```
In arch/powerpc/perf/callchain.c (c000000000124fa0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/perf/callchain.c:read_user_stack_slow
```
```
In arch/powerpc/perf/core-book3s.c (c000000000127b04)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:power_pmu_del
  - arch/powerpc/perf/core-book3s.c:power_pmu_add
  - arch/powerpc/perf/core-book3s.c:power_pmu_enable
  - arch/powerpc/perf/core-book3s.c:power_pmu_enable
  - arch/powerpc/perf/core-book3s.c:power_pmu_disable
  - arch/powerpc/perf/core-book3s.c:perf_event_print_debug
```
```
In kernel/cpu.c (c000000001365f20)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
```
```
In kernel/softirq.c (c000000000146960)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
```
```
In kernel/workqueue.c (c000000000165b14)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/kthread.c (c000000000173918)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/core.c (c00000000018be54)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:yield_to
```
```
In kernel/sched/debug.c (c0000000001b6044)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/sched/membarrier.c (c0000000001bdb88)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_exec_mmap
```
```
In kernel/locking/percpu-rwsem.c (c0000000001c2190)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In kernel/locking/spinlock.c (c000000000eeac38)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
```
In kernel/printk/printk.c (c0000000001ca9a4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_safe.c (c0000000001d08cc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_exit
  - kernel/printk/printk_safe.c:__printk_safe_enter
  - kernel/printk/printk_safe.c:printk_nmi_direct_exit
  - kernel/printk/printk_safe.c:printk_nmi_direct_enter
  - kernel/printk/printk_safe.c:printk_nmi_exit
  - kernel/printk/printk_safe.c:printk_nmi_enter
```
```
In kernel/rcu/srcutree.c (c0000000001e4c98)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__srcu_read_unlock
  - kernel/rcu/srcutree.c:__srcu_read_lock
```
```
In kernel/rcu/tree.c (c0000000001eaf60)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/rcu/tree.c:rcu_idle_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In kernel/profile.c (c0000000001f9280)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In kernel/time/clockevents.c (c00000000021603c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_update_freq
```
```
In kernel/time/tick-oneshot.c (c000000000219b20)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/time/tick-oneshot.c:tick_oneshot_mode_active
```
```
In kernel/time/tick-sched.c (c00000000021b46c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
```
```
In kernel/smp.c (c000000000223b70)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - kernel/smp.c:generic_exec_single
```
```
In kernel/cgroup/cgroup.c (c0000000002462fc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a75c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024c838)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c00000000024e2dc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c0000000002552fc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/stop_machine.c (c000000000259088)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/debug_core.c (c000000000271b50)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (c000000000275478)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/relay.c (c0000000002897d0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/taskstats.c (c00000000028b130)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In kernel/tsacct.c (c00000000028c3f0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
```
```
In kernel/trace/trace_clock.c (c00000000028d57c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (c00000000028e7cc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/ring_buffer.c (c00000000029e6cc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (c0000000002a7454)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:put_trace_buf
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:disable_trace_buffered_event
  - kernel/trace/trace.c:enable_trace_buffered_event
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (c0000000002b94f0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bb16c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
```
```
In kernel/trace/trace_stack.c (c0000000002bd380)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_functions_graph.c (c0000000002be2f8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (c0000000002c3e00)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
```
In kernel/trace/trace_events.c (c0000000002c7f0c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
```
In kernel/trace/trace_syscalls.c (c0000000002cdabc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/bpf_trace.c (c0000000002ea38c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:put_bpf_raw_tp_regs
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/trace/trace_kprobe.c (c0000000002eed34)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (c0000000002fc340)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
```
In kernel/bpf/syscall.c (c000000000308bd0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (c00000000031ef4c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/arraymap.c (c000000000324abc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/percpu_freelist.c (c000000000325ad4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
```
In kernel/bpf/devmap.c (c0000000003325f0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (c0000000003364ec)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In kernel/bpf/cgroup.c (c000000000339f40)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (c000000000350e90)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_sched_cb_inc
  - kernel/events/core.c:perf_sched_cb_dec
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_cgroup_switch
```
```
In mm/filemap.c (c000000000368ce0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (c00000000036fabc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (c00000000037385c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/swap.c (c00000000037c3e4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (c00000000038b434)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (c0000000003928d8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (c000000000399960)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:mod_node_page_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:mod_zone_page_state
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/backing-dev.c (c00000000039f1ac)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/mmu_context.c (c00000000039f7bc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/slab_common.c (c0000000003a9538)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/compaction.c (c0000000003b0b38)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/workingset.c (c0000000003b4d34)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/gup.c (c0000000003b7994)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/memory.c (c0000000003c4470)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (c0000000003c904c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (c0000000003d2a30)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_alloc.c (c0000000003edd74)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/page_io.c (c0000000003f5d20)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (c0000000003f80a4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/mempolicy.c (c000000000414800)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/slub.c (c00000000042c670)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (c000000000439d44)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (c000000000444060)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c000000000449188)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In mm/memcontrol.c (c00000000045b130)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:mod_memcg_obj_state
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (c00000000045d86c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (c000000000461370)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (c00000000046da74)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (c000000000470a2c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/exec.c (c000000000485ccc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In fs/dcache.c (c0000000004a13e0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_lru_shrink_move
  - fs/dcache.c:d_shrink_add
  - fs/dcache.c:d_shrink_del
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
  - fs/dcache.c:d_lru_add
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (c0000000004a96c8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_list_add
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (c0000000004b5670)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs-writeback.c (c0000000004cc58c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (c0000000004de17c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/block_dev.c (c0000000004e73d4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (c0000000004efaac)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/eventfd.c (c0000000004fda60)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_signal
  - fs/eventfd.c:eventfd_signal
```
```
In fs/aio.c (c000000000505254)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_compat_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_compat_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:put_reqs_available
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (c00000000050e744)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In fs/dax.c (c0000000005164cc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In fs/drop_caches.c (c0000000005394d4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/ext4/page-io.c (c0000000005d01dc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In security/selinux/avc.c (c00000000069d654)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_free
```
```
In security/selinux/netif.c (c0000000006b615c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (c0000000006e0770)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In block/bio.c (c00000000076b658)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In block/blk-core.c (c000000000778040)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (c000000000780cdc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In block/blk-softirq.c (c0000000007816c8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:trigger_softirq
```
```
In block/blk-mq.c (c000000000783d74)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c00000000078c02c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-mq-sched.c (c00000000078f68c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c0000000007abdc4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c0000000007afa10)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (c0000000007b3e98)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In lib/random32.c (c0000000007cc300)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - lib/random32.c:__prandom_reseed
```
```
In lib/percpu-refcount.c (c0000000007dadc0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/percpu_counter.c (c000000000811530)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_add_batch
```
```
In lib/irq_poll.c (c00000000081cee4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/sbitmap.c (c0000000008204ec)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - lib/sbitmap.c:__sbitmap_queue_get
  - lib/sbitmap.c:__sbitmap_queue_get
```
```
In drivers/tty/serial/8250/8250_port.c (c000000000933b70)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
```
```
In drivers/char/random.c (c0000000009458e8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
```
```
In drivers/block/loop.c (c0000000009c793c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/nvdimm/region_devs.c (c000000000a05ca0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (c000000000a19fe0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In drivers/scsi/scsi_lib.c (c000000000a326dc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-scsi.c (c000000000a69774)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/spi/spi-fsl-spi.c (c000000000a8dc24)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
```
```
In drivers/net/tun.c (c000000000aa2c30)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b13094)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/md/md.c (c000000000bd6ea4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In drivers/edac/edac_mc.c (0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (c000000000c088e8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c59d54)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/sock.c (c000000000c7ebac)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/sock.c:sock_inuse_add
```
```
In net/core/dev.c (c000000000cb76d0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (c000000000cbce80)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (c000000000cc1fec)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (c000000000cc6768)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (c000000000cd8398)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (c000000000cd8ce8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/filter.c (c000000000cdcf6c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/net-sysfs.c (c000000000cf7290)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (c000000000cfdda4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:queue_process
```
```
In net/core/drop_monitor.c (c000000000d0abb4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
```
```
In net/core/netprio_cgroup.c (c000000000d0e6f8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (c000000000d10150)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (c000000000d294f8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (c000000000d33360)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_api.c (c000000000d36780)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (c000000000d49808)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (c000000000d5222c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_queue.c (c000000000d56340)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (c000000000d5f7b8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_forward.c (c000000000d6344c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c000000000d69da0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/ip_sockglue.c (c000000000d6d7cc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d76dd0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (c000000000d85040)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c000000000d90ef4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tasklet_func
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9c45c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e340)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_fastopen.c (c000000000da4928)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (c000000000da4dcc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (c000000000da72cc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c000000000da8cc8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In net/ipv4/udp.c (c000000000daf274)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (c000000000db8b00)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/devinet.c (c000000000dbe168)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:in_dev_finish_destroy
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/af_inet.c (c000000000dc1824)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
```
```
In net/ipv4/fib_semantics.c (c000000000dd0608)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/fib_trie.c (c000000000dd61dc)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
```
In net/ipv4/ping.c (c000000000ddbe48)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (c000000000de8cf0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/tcp_cubic.c (c000000000df1270)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/ipv4/xfrm4_policy.c (c000000000df715c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (c000000000df9ad0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_state.c (c000000000e05730)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (c000000000e0f140)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e10a00)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_device.c (c000000000e1274c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (c000000000e1f0d0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (c000000000e32830)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (c000000000e44a50)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4db44)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
```
```
In net/ipv6/ndisc.c (c000000000e5172c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c000000000e556b0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c000000000e5aaf4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (c000000000e5d878)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (c000000000e61128)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b434)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
```
```
In net/ipv6/ping.c (c000000000e6d7ac)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (c000000000e7c0c4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7dbac)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e690)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/netfilter.c (c000000000e8013c)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/addrconf_core.c (c000000000e8b430)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (c000000000e923d4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea5c28)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (c000000000eb25e8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebb9c4)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (c000000000ebe3a8)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (c000000000ec0e80)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
```
In lib/dump_stack.c (c000000000ec3db0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (c000000000ec88c0)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In lib/ratelimit.c (c000000000ed1b90)
Location: arch/powerpc/include/asm/hw_irq.h:111
Inline: True
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
