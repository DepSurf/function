# Function: <code>instrument_atomic_read_write</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/panic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/resource.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/user.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/umh.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/nsproxy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/ucount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/usermode_driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/loadavg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/stop_task.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/resend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/stacktrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/utsname.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/jump_label.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/prfile.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmu_gather.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/msync.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/frontswap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/zpool.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/file_table.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fs_struct.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fs_context.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/init.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/notification.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/group.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/iomap/seek.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/root.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/item.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/misc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/process_keys.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/group.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/network.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/audit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/capability.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/task.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/match.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/domain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/resource.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/mount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/net.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/iint.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/algapi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/rng.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-ioc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/keyslot-manager.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/refcount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/syscall.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/irq_poll.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/dump_stack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/klist.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/kobject.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/ioasid.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dax/bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/request_sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/link_watch.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/gro_cells.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/ematch.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/scm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ping.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/token.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/syncookies.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/instrumented.h:99
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
Location: include/linux/instrumented.h:99
Inline: True
```
```
In init/do_mounts.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/panic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/resource.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/user.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/umh.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/nsproxy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/ucount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/usermode_driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/loadavg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/stop_task.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/resend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/stacktrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/misc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/utsname.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/jump_label.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmu_gather.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/msync.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/frontswap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/zpool.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/file_table.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fs_struct.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fs_context.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/init.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/notification.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/group.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/root.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/item.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/misc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/process_keys.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/group.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/network.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/audit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/capability.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/task.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/match.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/domain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/resource.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/mount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/net.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/landlock/cred.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/landlock/fs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/iint.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/algapi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-ioc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/keyslot-manager.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/refcount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/syscall.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/irq_poll.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/buildid.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/dump_stack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/klist.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/kobject.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/ioasid.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dax/bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/request_sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/link_watch.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/gro_cells.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/ematch.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/udp_bpf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/scm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ping.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/token.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/syncookies.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/instrumented.h:99
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
Location: include/linux/instrumented.h:99
Inline: True
```
```
In init/do_mounts.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/panic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/resource.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/user.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/umh.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/nsproxy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/ucount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/usermode_driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/loadavg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/stop_task.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/core_sched.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/resend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/stacktrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/misc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/utsname.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/jump_label.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/prfile.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmu_gather.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/msync.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/frontswap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/zpool.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/secretmem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/bootmem_info.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/file_table.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fs_struct.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fs_context.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/init.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/notification.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/group.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/root.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/item.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/misc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/process_keys.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/group.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/network.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/audit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/capability.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/task.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/match.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/domain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/resource.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/mount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/net.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/landlock/cred.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/landlock/fs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/iint.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/algapi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-ioc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/keyslot-manager.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/refcount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/syscall.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/irq_poll.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/ubsan.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/buildid.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/klist.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/kobject.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/ioasid.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/iommu-sva-lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dax/bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/request_sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/link_watch.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/gro_cells.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/ematch.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/udp_bpf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/unix_bpf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/scm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ping.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/token.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/instrumented.h:99
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
Location: include/linux/instrumented.h:99
Inline: True
```
```
In init/do_mounts.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/panic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/user.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/umh.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/nsproxy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/ucount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/usermode_driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/resend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/stacktrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/time/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/cgroup/misc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/utsname.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/trace/rethook.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/jump_label.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/prfile.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmu_gather.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/msync.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/frontswap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/zpool.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/secretmem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In mm/bootmem_info.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/file_table.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fs_context.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/init.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/notification.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/group.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/root.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/configfs/item.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/misc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In ipc/namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/process_keys.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/group.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/network.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/audit.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/capability.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/task.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/match.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/domain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/resource.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/mount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/net.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/landlock/cred.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/landlock/fs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/algapi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/bdev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-ioc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-cgroup-fc-appid.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In block/blk-crypto-profile.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/refcount.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/syscall.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/irq_poll.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/ubsan.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/buildid.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/klist.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/kobject.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/iommu/iommu-sva-lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dax/bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cxl/core/suspend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In drivers/hte/hte.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/request_sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/link_watch.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/udp_bpf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/unix_bpf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/unix/scm.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ping.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/token.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/linux/instrumented.h:99
Inline: True
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/instrumented.h:99
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
Location: include/linux/instrumented.h:100
Inline: True
```
```
In init/do_mounts.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/panic.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/user.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/umh.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/nsproxy.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/ucount.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/usermode_driver.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/irq/resend.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/stacktrace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/time/namespace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/cgroup/misc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/utsname.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/trace/rethook.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/memalloc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/cgroup_iter.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/bpf_cgrp_storage.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/jump_label.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/prfile.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/mmu_gather.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/msync.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/frontswap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/zpool.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/secretmem.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In mm/bootmem_info.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/file_table.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/fs_context.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/init.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/proc_namespace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/notify/notification.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/notify/group.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/proc/inode.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/proc/root.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/configfs/inode.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/configfs/dir.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/configfs/item.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In ipc/namespace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/keys/process_keys.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/tomoyo/group.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/tomoyo/network.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/audit.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/capability.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/task.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/match.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/domain.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/resource.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/file.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/mount.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/net.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/apparmor/notify.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/safesetid/lsm.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/landlock/cred.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/landlock/fs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In crypto/algapi.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/bdev.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/elevator.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-ioc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-cgroup-fc-appid.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In block/blk-crypto-profile.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/uring_cmd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/net.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/msg_ring.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/timeout.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/fdinfo.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/poll.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/cancel.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/notif.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/refcount.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/syscall.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/irq_poll.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/ubsan.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/pci/pcie/portdrv.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/dma/hsu/hsu.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/iommu/iommu-sva.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/base/memory.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/dax/bus.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/cxl/core/suspend.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/md/dm-io-rewind.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In drivers/hte/hte.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/request_sock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/link_watch.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/udp_bpf.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/unix/unix_bpf.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/unix/scm.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/ping.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/mptcp/token.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/buildid.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/klist.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/kobject.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/instrumented.h:100
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/instrumented.h:100
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
Location: include/linux/instrumented.h:94
Inline: True
```
```
In init/do_mounts.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/msr.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/intel/bts.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/xen/p2m.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/mm/pat/memtype.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/panic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/resource.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/user.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/umh.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/nsproxy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/ucount.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/usermode_driver.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/vhost_task.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/resend.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/stacktrace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/dma.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/misc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/utsname.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/watchdog_perf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/rethook.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/memalloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/cgroup_iter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/bpf_cgrp_storage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/cpumask.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/jump_label.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mmzone.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mmu_gather.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/msync.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/frontswap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/zpool.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/secretmem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/bootmem_info.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/file_table.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fs_pin.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fs_context.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/init.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/mnt_idmapping.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc_namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/notify/notification.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/notify/group.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/crypto/hooks.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/crypto/inline_crypt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/verity/open.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/root.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/configfs/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/configfs/dir.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/configfs/item.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/squashfs/block.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In ipc/namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/process_keys.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/group.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/network.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/audit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/capability.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/task.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/domain.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/resource.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/mount.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/net.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/notify.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/safesetid/lsm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/landlock/cred.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/landlock/fs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/algapi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/aead.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/geniv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/akcipher.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/sig.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/dh.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/rng.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/jitterentropy-testing.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/bdev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/elevator.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-ioc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-cgroup-fc-appid.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-crypto-profile.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/net.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/msg_ring.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/timeout.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/fdinfo.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/poll.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/cancel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/kbuf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/notif.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In rust/helpers.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/lockref.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/debug_locks.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/llist.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/refcount.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/rcuref.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/errseq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/generic-radix-tree.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/syscall.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/irq_poll.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/ubsan.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/group_cpus.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/pcie/portdrv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/pcie/err.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/vgaarb.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma/hsu/hsu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/intel/perfmon.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/iommu-sva.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/memory.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dax/bus.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/cxl/core/suspend.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-io-rewind.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_dispatch.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/hte/hte.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/request_sock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/link_watch.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netfilter/nf_log.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netfilter/nf_bpf_link.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/protocol.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/datagram.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/udp_bpf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/unix/unix_bpf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/unix/scm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ping.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/protocol.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/devlink/leftover.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/devlink/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/devlink/dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/token.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/mib.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/handshake/netlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/handshake/request.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/buildid.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/klist.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/kobject.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/instrumented.h:94
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
Location: include/linux/instrumented.h:94
Inline: True
```
```
In init/do_mounts.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/msr.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/intel/bts.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/xen/p2m.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/mm/pat/memtype.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/panic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/resource.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/user.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/umh.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/nsproxy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/ucount.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/vhost_task.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/printk/nbcon.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/resend.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/stacktrace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/time/namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/dma.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/crash_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/cgroup/misc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/utsname.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/watchdog_perf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/irq_work.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/memalloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/tcx.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/cgroup_iter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/bpf_cgrp_storage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/bpf/cpumask.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/jump_label.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/shrinker.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mmzone.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mmu_gather.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/msync.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/zpool.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/secretmem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In mm/bootmem_info.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/file_table.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fs_pin.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fs_context.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/init.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/mnt_idmapping.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc_namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/notify/notification.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/notify/group.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/crypto/hooks.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/crypto/inline_crypt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/verity/open.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/backing-file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/root.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/configfs/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/configfs/dir.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/configfs/item.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/squashfs/block.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In fs/tracefs/event_inode.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In ipc/namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/process_keys.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/group.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/network.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/audit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/capability.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/task.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/domain.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/resource.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/mount.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/net.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/af_inet.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/apparmor/notify.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/safesetid/lsm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/landlock/cred.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/landlock/fs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/algapi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/aead.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/geniv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/lskcipher.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/akcipher.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/sig.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/dh.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/rng.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/bdev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/elevator.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-ioc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-cgroup-fc-appid.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In block/blk-crypto-profile.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/net.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/msg_ring.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/timeout.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/poll.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/cancel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/notif.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/waitid.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/register.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In io_uring/futex.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In rust/helpers.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/lockref.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/debug_locks.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/llist.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/lwq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/refcount.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/rcuref.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/errseq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/generic-radix-tree.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/syscall.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/closure.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/irq_poll.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/stackdepot.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/ubsan.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/group_cpus.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/pcie/portdrv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/pcie/err.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pci/vgaarb.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma/hsu/hsu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/pmdomain/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/regulator/event.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/intel/perfmon.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/iommu/iommu-sva.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/memory.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dax/bus.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/cxl/core/suspend.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_atomic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_auth.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_client.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_client_modeset.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_color_mgmt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_connector.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_drv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_file.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_framebuffer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_gem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_mode_object.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_modeset_lock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_prime.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_syncobj.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_vblank.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_writeback.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/accel/drm_accel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_gem_shmem_helper.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_atomic_helper.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_atomic_state_helper.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_damage_helper.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_gem_atomic_helper.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_gem_framebuffer_helper.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_self_refresh_helper.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/gpu/drm/drm_fb_helper.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/netkit.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/md/dm-io-rewind.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_dispatch.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/hte/hte.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In drivers/dpll/dpll_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/request_sock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/link_watch.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netfilter/nf_log.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netfilter/nf_bpf_link.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/protocol.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/datagram.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_sigpool.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/udp_bpf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv4/tcp_ao.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xfrm/xfrm_state_bpf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/unix/unix_bpf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/unix/scm.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ping.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/protocol.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/devlink/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/devlink/dev.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/devlink/rate.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/options.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/token.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/mib.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/handshake/netlink.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/handshake/request.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In net/handshake/tlshd.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/buildid.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/klist.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/kobject.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/instrumented.h:94
Inline: True
```
```
In lib/objpool.c (0)
Location: include/linux/instrumented.h:94
Inline: True
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
