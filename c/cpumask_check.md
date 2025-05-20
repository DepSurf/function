# Function: <code>cpumask_check</code>

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
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/events/intel/cqm.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/events/intel/cstate.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/events/intel/rapl.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/setup.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/topology.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/main.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/setup_percpu.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/kgdb.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/sched/stats.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/sched/cpuacct.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/locking/lglock.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/rcu/srcu.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/time/timer_stats.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/debug/gdbstub.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/mmu_context.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/proc/uptime.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/proc/softirqs.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In block/elevator.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In block/blk-iopoll.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In block/blk-mq-sysfs.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In lib/swiotlb.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In lib/iommu-common.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_errprint.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/acpi/processor_core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/acpi/processor_thermal.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/base/topology.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/dma-buf/fence.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/cpufreq/cpufreq_stats.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In arch/x86/pci/amd_bus.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/core/flow.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/cpumask.h:114
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/cpumask.h:114
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
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/cqm.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/setup.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/topology.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/main.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/setup_percpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/kgdb.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/stats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/cpuacct.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/locking/lglock.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/printk/nmi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/rcu/srcu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/timer_stats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/debug/gdbstub.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/proc/uptime.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/proc/softirqs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/elevator.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq-sysfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/swiotlb.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/iommu-common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/irq_poll.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_errprint.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_thermal.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/topology.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/dma-buf/fence.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/pci/amd_bus.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/flow.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/cpumask.h:118
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
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/cqm.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/setup.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/topology.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_schemata.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/main.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/setup_percpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/kgdb.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/itmt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/stats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/cpuacct.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/printk/nmi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/rcu/srcu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/timer_stats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/cgroup.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/debug/gdbstub.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/proc/uptime.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/proc/softirqs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/elevator.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq-sysfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq-pci.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/swiotlb.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/iommu-common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/irq_poll.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_errprint.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_thermal.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/flow.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/proc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/xfrm/xfrm_proc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/proc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/cpumask.h:118
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
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/xen/smp_hvm.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/setup.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/irqinit.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/topology.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/main.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/setup_percpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/kgdb.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/kernel/itmt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/stats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/cpuacct.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/debug/gdbstub.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/inode.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/proc/uptime.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/proc/softirqs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/elevator.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq-sysfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq-pci.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-mq-virtio.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/swiotlb.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/iommu-common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/irq_poll.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_errprint.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_thermal.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/flow.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/core/gro_cells.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv4/proc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/xfrm/xfrm_proc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/proc.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:118
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:118
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
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/main.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/bpf/inode.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/elevator.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In lib/swiotlb.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_errprint.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:119
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
In init/main.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In security/security.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/elevator.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:119
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:119
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
In init/main.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:126
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
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:126
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:126
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
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:142
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
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/iomap/apply.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:142
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
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/iomap/apply.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:142
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
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/iomap/apply.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/cpumask.h:113
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
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/kfence/report.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/iomap/iter.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/cpumask.h:113
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
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/panic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/kfence/report.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/iomap/iter.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/ata/ata_piix.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/amd-pstate.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/cpumask.h:113
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/linux/cpumask.h:113
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
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/panic.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/kfence/report.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/iomap/iter.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In io_uring/timeout.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In io_uring/poll.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/ata/ata_piix.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/watchdog/watchdog_core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/cpufreq/amd-pstate.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/cpuidle/governors/haltpoll.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In lib/maple_tree.c (0)
Location: include/linux/cpumask.h:115
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:115
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
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/panic.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/notifier.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/module/kmod.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/watchdog_perf.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/bpf/cpumask.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/kfence/report.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/iomap/iter.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/timeout.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/poll.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In lib/group_cpus.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/iommu/intel/perfmon.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/ata/ata_piix.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/watchdog/watchdog_core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpufreq/amd-pstate.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpuidle/governors/haltpoll.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/devlink/leftover.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/devlink/health.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/handshake/netlink.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/handshake/request.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In lib/maple_tree.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:148
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
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/debugfs.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/panic.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/notifier.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/module/kmod.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/watchdog_perf.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/bpf/cpumask.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/context_tracking.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/shrinker.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/kfence/report.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/iomap/iter.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/timeout.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/poll.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/register.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In lib/group_cpus.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/pmdomain/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/iommu/intel/perfmon.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/ata/ata_piix.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/gpu/drm/drm_vblank.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/watchdog/watchdog_core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpufreq/amd-pstate.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/cpuidle/governors/haltpoll.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv4/tcp_sigpool.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/devlink/health.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/devlink/trap.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/handshake/alert.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/handshake/netlink.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In net/handshake/request.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In lib/maple_tree.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:148
Inline: True
```
```
In lib/objpool.c (0)
Location: include/linux/cpumask.h:148
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
In init/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm64/kernel/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm64/kernel/ptrace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm64/kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm64/kernel/armv8_deprecated.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm64/mm/context.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm64/mm/numa.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In virt/kvm/kvm_main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In virt/kvm/eventfd.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In virt/kvm/arm/arm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In virt/kvm/arm/mmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In virt/kvm/arm/mmio.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm64/kvm/handle_exit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm64/kvm/guest.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm64/kvm/debug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm64/kvm/sys_regs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In virt/kvm/arm/vgic/vgic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In virt/kvm/irqchip.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In virt/kvm/arm/arch_timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/irqchip/irq-partition-percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/irqchip/irq-bcm7038-l1.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pci/controller/pci-xgene-msi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pci/controller/pcie-iproc-msi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/soc/fsl/qbman/bman_portal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/soc/fsl/qbman/qman_portal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/soc/fsl/qbman/bman.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/soc/fsl/qbman/qman.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/soc/qcom/rpmh-rsc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/arch_topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/cpu_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/of.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/clocksource/arm_arch_timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/perf/arm_pmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/perf/arm_pmu_platform.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/perf/arm_pmu_acpi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/perf/qcom_l2_pmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/perf/qcom_l3_pmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/perf/xgene_pmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:142
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
In init/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/kernel/ptrace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/kernel/devtree.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/kernel/hw_breakpoint.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mm/flush.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mm/context.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mm/cache-l2x0-pmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/common/bL_switcher.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mach-exynos/pm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mach-imx/mmdc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mach-imx/platsmp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mach-omap2/omap-smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mach-omap2/pm34xx.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mach-omap2/cpuidle44xx.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mach-omap2/powerdomain.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mach-qcom/platsmp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mach-tegra/cpuidle-tegra20.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/arm/mach-tegra/platsmp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/mmu_context.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/irqchip/irq-partition-percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma/tegra20-apb-dma.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/soc/qcom/spm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/arch_topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/ethernet/ti/cpsw.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/musb/musb_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/musb/musb_trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/musb/musb_host.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/musb/musb_gadget.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/gadget/udc/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/cpu_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/of.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpuidle/coupled.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpuidle/cpuidle-big_little.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/firmware/qcom_scm-32.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/clocksource/arm_arch_timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/perf/arm_pmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/perf/arm_pmu_platform.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In sound/soc/soc-dapm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In sound/soc/soc-jack.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:142
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
In init/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/ptrace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/irq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/sysfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/time.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/setup-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/watchdog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/rtas.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/dbell.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/stacktrace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/crash.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kernel/machine_kexec_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/mm/mmu_context.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_pgtable.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/mm/book3s64/pgtable.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_tlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_native.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/mm/numa.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/sysdev/mpic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/sysdev/xics/xics-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/sysdev/xics/icp-native.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/sysdev/xive/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-call.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/platforms/powernv/idle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/platforms/powernv/vas-window.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/platforms/pseries/lpar.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/platforms/pseries/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/platforms/pseries/rtas-fadump.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/xmon/xmon.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/powerpc/perf/imc-pmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_nvlink2.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/cpu_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/of.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/powernv-cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:142
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
In init/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/riscv/kernel/ptrace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/riscv/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/riscv/kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/riscv/mm/cacheflush.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/riscv/mm/context.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/arch_topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/of.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:142
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
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/nvme/host/multipath.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/nvme/host/pci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:142
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
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/stop_task.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/context_tracking.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/storvsc_drv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/nvme/host/multipath.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/nvme/host/pci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hv/vmbus_drv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hv/connection.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hv/channel.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hv/channel_mgmt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:142
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
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/netfilter/nf_conntrack_standalone.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/netfilter/nf_conntrack_netlink.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:142
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
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-softirq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/fair_share.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/step_wise.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/cpumask.h:142
Inline: True
```
</details>
</li>
</ul>

## Differences
