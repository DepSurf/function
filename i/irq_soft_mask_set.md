# Function: <code>irq_soft_mask_set</code>

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
In init/main.c (c000000001343d54)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/powerpc/kernel/irq.c (c00000000001b71c)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - arch/powerpc/kernel/irq.c:prep_irq_for_idle
  - arch/powerpc/kernel/irq.c:restore_interrupts
```
```
In arch/powerpc/kernel/time.c (c00000000002bd20)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:arch_suspend_disable_irqs
```
```
In arch/powerpc/kernel/setup-common.c (c00000000003037c)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:machine_hang
```
```
In arch/powerpc/kernel/setup_64.c (c00000000003110c)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup_64.c:early_setup_secondary
  - arch/powerpc/kernel/setup_64.c:early_setup
  - arch/powerpc/kernel/setup_64.c:early_setup
```
```
In arch/powerpc/kernel/smp.c (c0000000000558ec)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:generic_cpu_disable
```
```
In arch/powerpc/kernel/machine_kexec_64.c (c000000000071728)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec
  - arch/powerpc/kernel/machine_kexec_64.c:kexec_smp_down
```
```
In arch/powerpc/kernel/kvm.c (c000000001353e74)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - arch/powerpc/kernel/kvm.c:kvm_guest_init
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009fd48)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c0000000000cd088)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_handle_events
```
```
In arch/powerpc/platforms/pseries/iommu.c (c0000000000efc98)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/iommu.c:tce_setrange_multi_pSeriesLP
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9ba8)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_mach_cpu_die
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_mach_cpu_die
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_mach_cpu_die
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_mach_cpu_die
```
```
In kernel/panic.c (c00000000013c824)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/cpu.c (c00000000013fe40)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_thread_fun
```
```
In kernel/softirq.c (c000000000146a68)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__do_softirq
```
```
In kernel/workqueue.c (c000000000169b70)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:rcu_work_rcufn
```
```
In kernel/sched/core.c (c0000000001853f8)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/clock.c (c00000000136991c)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init
```
```
In kernel/sched/idle.c (c00000000018ed44)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (c000000000193308)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/psi.c (c0000000001bf5f0)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
```
In kernel/locking/spinlock.c (c000000000eeab50)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
```
```
In kernel/power/suspend.c (c0000000001c87e8)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/power/suspend.c:arch_suspend_disable_irqs
```
```
In kernel/printk/printk.c (c0000000001cdc20)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/irq/handle.c (c0000000001d2788)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/spurious.c (c0000000001d7874)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/resend.c (c0000000001d80b0)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/rcu/tree.c (c0000000001eb7e4)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (c000000000203d08)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/time/tick-sched.c (c00000000021b270)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
```
```
In kernel/cgroup/cpuset.c (c00000000024f028)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/stop_machine.c (c000000000259080)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace.c (c0000000002b00d8)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc490)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_stack.c (c0000000002bd198)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
```
```
In mm/gup.c (c0000000003ba004)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
```
```
In mm/slub.c (c000000000427a0c)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:allocate_slab
```
```
In mm/memcontrol.c (c00000000045b214)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/buffer.c (c0000000004dec50)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
```
```
In block/blk-softirq.c (c0000000007814dc)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:blk_done_softirq
```
```
In lib/irq_poll.c (c00000000081d064)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/mfd/ezx-pcap.c (c0000000009ea1c8)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
```
In drivers/usb/core/hcd-pci.c (c000000000af4dac)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/md/dm-stats.c (c000000000bfee20)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__dm_stat_clear
  - drivers/md/dm-stats.c:__dm_stat_clear
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
```
```
In drivers/cpuidle/cpuidle.c (c000000000c1e444)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/cpuidle-pseries.c (c000000000c22650)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-pseries.c:shared_cede_loop
  - drivers/cpuidle/cpuidle-pseries.c:dedicated_cede_loop
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
```
```
In drivers/cpuidle/cpuidle-powernv.c (c000000000c22bcc)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
```
```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c59e50)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (c000000000cacdcc)
Location: arch/powerpc/include/asm/hw_irq.h:83
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
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
