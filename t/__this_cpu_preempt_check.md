# Function: <code>__this_cpu_preempt_check</code>

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
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/events/intel/rapl.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/rcu/srcu.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In lib/idr.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In lib/iommu-common.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:300
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
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/rcu/srcu.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In lib/idr.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In lib/iommu-common.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/rcu/srcu.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In lib/idr.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In lib/iommu-common.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
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
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In lib/iommu-common.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:300
Inline: True
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
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In lib/iommu-common.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
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
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:315
Inline: True
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
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
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
In init/main.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/time/tick-broadcast-hrtimer.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In lib/dump_stack.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:314
Inline: True
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
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/dump_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
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
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpuacct.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/dump_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
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
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/sev-es.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpuacct.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/dump_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
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
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpuacct.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/dump_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpuacct.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/pm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/pm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
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
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/context_tracking.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In mm/page-writeback.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/pm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
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
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/context_tracking.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/net_failover.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/pm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
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
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/nbcon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/context_tracking.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/gpu/drm/drm_flip_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/gpu/drm/drm_fb_helper.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/net_failover.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ao.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/pm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
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
In arch/arm64/kernel/fpsimd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm64/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm64/kernel/cpu_errata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm64/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm64/kernel/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm64/kernel/perf_event.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm64/kernel/probes/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm64/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In virt/kvm/arm/arm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm64/kvm/debug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle-psci.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/arm_arch_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
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
In arch/arm/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm/kernel/machine_kexec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm/kernel/perf_event_v7.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm/mm/highmem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm/probes/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/arm/probes/kprobes/opt-arm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/soc/qcom/spm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle-psci.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/arm_arch_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
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
In arch/powerpc/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kernel/sysfs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kernel/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kernel/mce.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kernel/dbell.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kernel/optprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kernel/kprobes-ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/sysdev/xive/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/platforms/pseries/lpar.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/platforms/pseries/iommu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/xmon/xmon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kvm/book3s_hv_ras.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/powerpc/perf/hv-24x7.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
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
In arch/riscv/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
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
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/dump_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
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
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/context_tracking.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/scsi/storvsc_drv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/hv/vmbus_drv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/hv/connection.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/hv/channel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/hv/channel_mgmt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/dump_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
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
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/netfilter/nf_conntrack_expect.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/dump_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
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
In init/main.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In init/calibrate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-oneshot.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/cpuidle/driver.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/i8253.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In drivers/clocksource/numachip.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/dump_stack.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
```
In arch/x86/lib/delay.c (0)
Location: include/linux/percpu-defs.h:313
Inline: True
```
</details>
</li>
</ul>

## Differences
