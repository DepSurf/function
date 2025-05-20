# Function: <code>system_has_prio_mask_debugging</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/debug-monitors.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/irq.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/process.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/ptrace.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/setup.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/signal.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/traps.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/insn.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/smp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/syscall.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/signal32.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/perf_callchain.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/perf_event.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/suspend.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/kgdb.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/armv8_deprecated.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/acpi.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/machine_kexec.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kernel/crash_dump.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/mm/fault.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/mm/context.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/kvm_main.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/eventfd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/vfio.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/arm/arm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/arm/psci.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kvm/guest.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kvm/sys_regs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kvm/fpsimd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/arm/vgic/vgic.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-v3.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-mmio.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-mmio-v2.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-kvm-device.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-its.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-debug.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/arm/arch_timer.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In virt/kvm/arm/pmu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/kvm/hyp/tlb.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm/xen/p2m.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/fork.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/panic.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/exit.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/softirq.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/capability.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/ptrace.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/user.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/signal.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sys.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/umh.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/task_work.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/kthread.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/notifier.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/async.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/ucount.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/groups.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/power/qos.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/irq/resend.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/irq/autoprobe.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/irq/pm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/rcu/sync.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/dma/coherent.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/kcmp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/freezer.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/profile.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/time.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/timer.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/uid16.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/module.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/acct.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/kexec.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/compat.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/cgroup/namespace.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/audit.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/seccomp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/relay.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/delayacct.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/taskstats.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/tsacct.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/trace/trace_clock.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/lpm_trie.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/queue_stack_maps.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In kernel/rseq.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/filemap.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/mempool.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/maccess.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/page-writeback.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/swap.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/truncate.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/vmscan.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/shmem.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/util.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/backing-dev.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/slab_common.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/compaction.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/list_lru.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/workingset.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/gup.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/memory.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/mincore.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/mlock.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/shuffle.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/swap_state.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/swap_slots.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/dmapool.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/slub.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/memory-failure.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/page_isolation.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/balloon_compaction.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/page_idle.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/hmm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In mm/memfd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/read_write.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/stat.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/exec.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/pipe.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/namei.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/fcntl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/ioctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/readdir.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/select.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/inode.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/filesystems.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/namespace.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/seq_file.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/xattr.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/libfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/splice.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/utimes.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/d_path.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/statfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/fs_pin.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/nsfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/fsopen.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/buffer.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/direct-io.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/eventpoll.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/signalfd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/timerfd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/eventfd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/aio.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/io_uring.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/dax.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/verity/enable.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/verity/measure.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/coredump.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/fhandle.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/quota/quota.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/proc/base.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/proc/page.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/configfs/file.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/dcookies.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/ext4/page-io.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/fat/dir.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/fat/file.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/pstore/inode.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In fs/efivarfs/file.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In ipc/compat.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In ipc/msgutil.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In ipc/msg.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In ipc/sem.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In ipc/shm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In ipc/mqueue.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/keys/keyring.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/keys/dh.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/keys/big_key.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/keys/trusted.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/selinux/avc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/selinux/ibpkey.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/apparmor/policy_ns.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In security/apparmor/label.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/bio.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/blk-flush.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/blk-ioc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/blk-softirq.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/blk-mq.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/ioctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/genhd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/badblocks.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/bsg.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/bsg-lib.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/blk-throttle.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/blk-iocost.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/mq-deadline.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/blk-zoned.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/sed-opal.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In block/blk-pm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/random32.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/iov_iter.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/kfifo.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/percpu-refcount.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/once.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/refcount.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/usercopy.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/kstrtox.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/checksum.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/strnlen_user.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/irq_poll.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/irqchip/irq-gic-common.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/irqchip/irq-bcm7038-l1.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/irqchip/irq-brcmstb-l2.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/irqchip/irq-mtk-sysirq.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/irqchip/irq-imx-gpcv2.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/irqchip/irq-mvebu-sei.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/irqchip/irq-imx-irqsteer.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/bus/hisi_lpc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/bus/fsl-mc/mc-sys.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pinctrl/pinctrl-rockchip.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/gpio/gpio-davinci.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/gpio/gpio-mpc8xxx.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/gpio/gpio-mvebu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/gpio/gpio-pl061.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/gpio/gpio-xgene.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/gpio/gpio-xilinx.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pci/access.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pci/syscall.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pci/controller/pcie-mobiveil.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pci/controller/dwc/pci-keystone.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/acpi/apei/erst.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/clk-divider.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/clk-gate.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/clk-multiplier.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/clk-mux.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/clk-fractional-divider.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/clk-xgene.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/hisilicon/clkgate-separated.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/hisilicon/clk-hisi-phase.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/hisilicon/reset.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/imx/clk-composite-8m.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/imx/clk-divider-gate.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/imx/clk-fixup-div.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/imx/clk-fixup-mux.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/imx/clk-gate2.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/imx/clk-pfdv2.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/imx/clk-lpcg-scu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/mediatek/clk-mux.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/meson/clk-mpll.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/renesas/rcar-gen3-cpg.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/rockchip/clk-cpu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/rockchip/clk-half-divider.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/rockchip/clk-inverter.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/rockchip/clk-ddr.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/rockchip/softrst.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi/clk-factors.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi/clk-a10-ve.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi/clk-mod0.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi/clk-sun4i-display.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi/clk-sun4i-tcon-ch1.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi/clk-usb.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi/clk-sun9i-cpus.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_mmc_timing.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_reset.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_div.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_frac.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_gate.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_mux.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_mult.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_phase.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_sdm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_nk.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_nkm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_nkmp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_nm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_mp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clk/versatile/clk-sp810.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/dma/virt-dma.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/dma/amba-pl08x.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/dma/bcm2835-dma.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/dma/ipu/ipu_irq.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/dma/ipu/ipu_idmac.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/soc/fsl/qbman/bman.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/soc/fsl/qbman/qman.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/soc/qcom/rpmh-rsc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/soc/qcom/rpmh.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/soc/renesas/rcar-sysc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/virtio/virtio.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/reset/reset-meson.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/reset/reset-simple.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/tty_ldisc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/tty_ldsem.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/8250/8250_fsl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/8250/8250_dw.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/8250/8250_mtk.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/imx.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/meson_uart.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/msm_serial.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/mvebu-uart.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/owl-uart.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/char/mem.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/char/ttyprintk.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/iommu/arm-smmu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/iommu/arm-smmu-v3.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/iommu/qcom_iommu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/devres.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/power/sysfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/power/common.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/block/loop.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/mfd/ab3100-core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/dma-buf/sync_debug.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/ata/libata-acpi.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/ata/libahci.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/spi/spi-fsl-spi.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/net/ethernet/smsc/smc91x.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/phy/phy.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/input/serio/serio.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/input/input.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/rtc/rtc-sun6i.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/pps/kapi.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/watchdog/watchdog_pretimeout.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/md/md.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/edac/altera_edac.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/mmc/core/queue.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/mmc/host/mmci.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/leds/led-triggers.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/firmware/ti_sci.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/firmware/arm_scmi/driver.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/firmware/efi/arm-runtime.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clocksource/sh_cmt.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/clocksource/sh_tmu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/of/base.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/of/dynamic.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/of/resolver.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/mailbox/pcc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/memory/fsl_ifc.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/perf/arm-cci.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/perf/arm-ccn.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/perf/qcom_l2_pmu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In drivers/perf/xgene_pmu.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/socket.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/sock.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/skbuff.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/datagram.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/scm.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/ethtool.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/link_watch.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/netpoll.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/compat.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv6/route.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/rfkill/core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/rfkill/input.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ncsi/ncsi-aen.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In arch/arm64/lib/uaccess_flushcache.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/dec_and_lock.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/dump_stack.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/idr.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/klist.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/ratelimit.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/seq_buf.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
```
In lib/xarray.c (0)
Location: arch/arm64/include/asm/cpufeature.h:610
Inline: True
```
</details>
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
