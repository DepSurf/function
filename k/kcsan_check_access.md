# Function: <code>kcsan_check_access</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/msr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/bts.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/knc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/setup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/p2m.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/efi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/setup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/quirks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/topology.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/i8253.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tsc_msr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/scattered.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/topology.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/rdrand.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/match.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/umwait.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/feat_ctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/tsx.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/intel_epb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/centaur.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/zhaoxin.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/setup_percpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/mpparse.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kgdb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/jailhouse.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/init_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/physaddr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/setup_nx.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pat/memtype.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/srat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pti.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/uv/bios_uv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/panic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/softirq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/resource.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/user.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sys.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/umh.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/pid.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/task_work.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/nsproxy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cred.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/async.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kmod.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/groups.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/loadavg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/clock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/idle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/rt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/wait.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/swait.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/completion.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/topology.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/stop_task.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/autogroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/debug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/psi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/process.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/suspend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/printk/printk_safe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/handle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/resend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/chip.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/migration.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/dma/pool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kcmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/freezer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/stacktrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/timer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/futex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/dma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/uid16.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/acct.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kexec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/compat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/utsname.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/audit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/gdbstub.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/hung_task.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/watchdog.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/relay.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/tsacct.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/reuseport_array.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/padata.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/iomem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/rseq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/oom_kill.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/maccess.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmzone.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mm_init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/percpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/workingset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/prfile.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/debug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmu_gather.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mprotect.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mremap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/msync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/vmalloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/process_vm_access.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/shuffle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memblock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/swap_slots.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/frontswap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/sparse.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_counter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/cleancache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/zpool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/frame_vector.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/usercopy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_reporting.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/open.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/file_table.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/super.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fcntl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/readdir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/select.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/dcache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/attr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/filesystems.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/sync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fs_struct.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fs_pin.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/nsfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fs_context.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/block_dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/mpage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/notification.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/mark.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/io_uring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/io-wq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/dax.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/fname.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/hooks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/bio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/verity/open.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/locks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/drop_caches.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/iomap/apply.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/iomap/seek.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/quota/netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/root.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/array.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/fd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/meminfo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/stat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/page.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/configfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/configfs/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/configfs/item.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/misc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/super.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/kthread.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/control.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/util.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/msg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/sem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/shm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/gc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/key.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/process_keys.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/group.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/network.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/audit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/capability.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/task.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/resource.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/net.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/iint.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_appraise.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/rng.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/elevator.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-flush.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-settings.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-ioc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-merge.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-softirq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/genhd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/amiga.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/atari.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/mac.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/msdos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/osf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/sgi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/sun.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/karma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/bounce.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/bsg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-cgroup-rwstat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-throttle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-iocost.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/mq-deadline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-wbt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq-debugfs-zoned.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-pm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/keyslot-manager.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/lockref.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/debug_locks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/bitmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/scatterlist.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/llist.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/rhashtable.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/refcount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/errseq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/generic-radix-tree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/genalloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/percpu_counter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/iommu-helper.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/syscall.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/irq_poll.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/sbitmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/cpumask.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/dump_stack.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/idr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/is_single_threaded.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/klist.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/kobject.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/radix-tree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/show_mem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/vsprintf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/xarray.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/kaslr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpio/gpio-xilinx.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/remove.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/console/dummycon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/processor_pdc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/manager.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/support.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/interface.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/misc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/amd/init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/irq_remapping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/connector/connector.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/dd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/syscore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/security.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/e820.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dax/super.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dax/bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/heaps/heap-helpers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/sync_debug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/loopback.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/linkmode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/bcm84881.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/touchscreen/of_touchscreen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/watchdog/watchdog_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/opp/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpuidle/poll_state.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/leds/led-triggers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/iscsi_ibft_find.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/efi-bgrt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/memattr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/memmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/secureboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ras/ras.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ras/cec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/request_sock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/datagram.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/stream.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/scm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/dst.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/neighbour.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/link_watch.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sock_diag.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/flow_offload.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/net-procfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/net-traces.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sock_map.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/dst_cache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/devlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/gro_cells.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/compat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethernet/eth.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/cls_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/ematch.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/bitset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/linkmodes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/protocol.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/datagram.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/metrics.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/unix/garbage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/unix/scm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_icmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/protocol.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/strparser/strparser.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/options.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/token.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/pm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/mib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/pci/xen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/pci/acpi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
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
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/msr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/intel/bts.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/intel/knc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/setup.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/p2m.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/xen/efi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/setup.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/quirks.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/topology.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/i8253.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/tsc_msr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/fpu/init.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/fpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/scattered.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/topology.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/rdrand.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/match.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/umwait.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/feat_ctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/tsx.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/intel_epb.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/centaur.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/zhaoxin.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/mce/apei.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/setup_percpu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/mpparse.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/kgdb.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/jailhouse.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/sev-es.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/init_64.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/physaddr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/setup_nx.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/pat/memtype.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/srat.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/mm/pti.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/platform/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/panic.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/cpu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/softirq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/resource.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/user.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sys.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/umh.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/pid.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/task_work.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/nsproxy.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/cred.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/async.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/usermode_driver.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/kmod.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/groups.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/loadavg.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/clock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/idle.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/rt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/wait.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/swait.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/completion.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/topology.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/stop_task.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/autogroup.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/debug.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/sched/psi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/power/process.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/power/suspend.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/printk/printk_safe.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq/handle.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq/resend.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq/chip.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq/migration.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/dma/mapping.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/dma/pool.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/entry/common.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/entry/kvm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/kcmp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/freezer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/stacktrace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/time/timer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/time/namespace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/futex.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/dma.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/uid16.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/acct.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/kexec.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/utsname.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/audit.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/debug/gdbstub.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/hung_task.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/watchdog.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/relay.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/tsacct.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/reuseport_array.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/padata.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/iomem.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/rseq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/oom_kill.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/maccess.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/mmzone.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/mm_init.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/percpu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/workingset.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/prfile.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/debug.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/mmap_lock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/mmu_gather.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/mprotect.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/mremap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/msync.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/vmalloc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/process_vm_access.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/memblock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/page_io.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/swap_slots.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/frontswap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/sparse.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/page_counter.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/cleancache.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/zpool.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/frame_vector.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/usercopy.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In mm/page_reporting.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/open.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/file_table.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/super.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fcntl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/readdir.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/select.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/dcache.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/inode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/attr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/filesystems.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/namespace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/sync.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fs_struct.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fs_pin.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/nsfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fs_context.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/init.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/remap_range.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/block_dev.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/mpage.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc_namespace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/notify/notification.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/notify/mark.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/io_uring.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/io-wq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/dax.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/crypto/hooks.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/crypto/bio.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/verity/open.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/locks.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/drop_caches.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/iomap/apply.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/iomap/seek.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/quota/netlink.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/inode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/root.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/array.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/fd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/meminfo.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/stat.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/proc/page.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/configfs/inode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/configfs/dir.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/configfs/item.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fat/dir.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fat/file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fat/misc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ecryptfs/super.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ecryptfs/kthread.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fuse/control.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fuse/xattr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fuse/acl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/fuse/dax.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In ipc/util.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In ipc/msg.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In ipc/sem.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In ipc/shm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/keys/gc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/keys/key.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/keys/process_keys.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/keys/proc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/tomoyo/file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/tomoyo/group.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/tomoyo/network.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/audit.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/capability.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/task.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/resource.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/net.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/integrity/iint.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/integrity/ima/ima_appraise.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In crypto/api.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In crypto/proc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In crypto/rng.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/elevator.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-sysfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-flush.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-settings.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-ioc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-merge.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-lib.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-mq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/ioctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/genhd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/amiga.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/atari.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/mac.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/msdos.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/osf.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/sgi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/sun.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/karma.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/bounce.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/bsg.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-cgroup-rwstat.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-throttle.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-iocost.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/mq-deadline.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-wbt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-mq-debugfs-zoned.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/keyslot-manager.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/lockref.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/debug_locks.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/random32.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/bitmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/scatterlist.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/llist.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/rhashtable.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/refcount.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/errseq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/generic-radix-tree.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/genalloc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/percpu_counter.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/iommu-helper.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/syscall.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/irq_poll.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/sbitmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/pldmfw/pldmfw.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/cpumask.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/dump_stack.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/idr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/is_single_threaded.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/klist.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/kobject.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/radix-tree.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/show_mem.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/vsprintf.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In lib/xarray.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/lib/kaslr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/gpio/gpio-xilinx.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/remove.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/video/console/dummycon.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/bus.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/processor_pdc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pnp/manager.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pnp/support.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pnp/interface.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/char/misc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/iommu/amd/init.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/iommu/ioasid.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/iommu/irq_remapping.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/connector/connector.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/dd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/syscore.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/power/main.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/nvdimm/security.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/nvdimm/e820.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dax/super.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dax/bus.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dma-buf/sync_debug.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/loopback.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/phy/linkmode.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/phy/bcm84881.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/input/touchscreen/of_touchscreen.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/watchdog/watchdog_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/md/dm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/opp/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/cpuidle/poll_state.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/iscsi_ibft_find.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/efi/efi-bgrt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/efi/memattr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/efi/memmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/efi/secureboot.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/firmware/efi/mokvar-table.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/ras/ras.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/ras/cec.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/request_sock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/datagram.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/stream.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/scm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/dev.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/dst.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/neighbour.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/link_watch.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/sock_diag.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/flow_offload.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/net-procfs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/net-traces.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/sock_map.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/dst_cache.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/devlink.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/gro_cells.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ethernet/eth.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/sched/cls_api.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/sched/ematch.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ethtool/common.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ethtool/bitset.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ethtool/linkmodes.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/protocol.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/datagram.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/metrics.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/proc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/unix/garbage.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/unix/scm.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/ping.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/proc.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/ip6_icmp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/protocol.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/strparser/strparser.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/mptcp/options.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/mptcp/token.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/mptcp/mib.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In net/mptcp/syncookies.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/pci/xen.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/pci/acpi.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/kcsan-checks.h:178
Inline: False
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
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/msr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/bts.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/knc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/setup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/p2m.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/efi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/setup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/quirks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/topology.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/i8253.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tsc_msr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/scattered.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/topology.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/rdrand.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/match.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/umwait.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/feat_ctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/tsx.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/intel_epb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/centaur.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/zhaoxin.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/apei.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/setup_percpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/mpparse.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kgdb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/paravirt-spinlocks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/jailhouse.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/init_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/physaddr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/setup_nx.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pat/memtype.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/srat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pti.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/panic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/softirq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/resource.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/user.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sys.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/umh.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/pid.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/task_work.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/nsproxy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cred.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/async.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/usermode_driver.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kmod.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/groups.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/loadavg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/clock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/idle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/rt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/wait.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/swait.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/completion.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/topology.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/stop_task.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/autogroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/debug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/psi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/process.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/suspend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/printk/printk_safe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/handle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/resend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/chip.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/migration.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/dma/mapping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/dma/pool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/entry/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/entry/kvm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kcmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/freezer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/stacktrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/timer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/futex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/dma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/uid16.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/acct.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kexec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/misc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/utsname.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/audit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/gdbstub.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/hung_task.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/watchdog.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/relay.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/tsacct.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/reuseport_array.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/padata.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/iomem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/rseq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/oom_kill.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/maccess.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmzone.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mm_init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/percpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/workingset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/debug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmap_lock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmu_gather.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mprotect.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mremap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/msync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/vmalloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/process_vm_access.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memblock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/swap_slots.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/frontswap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/sparse.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_counter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/cleancache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/zpool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/usercopy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_reporting.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/open.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/file_table.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/super.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fcntl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/readdir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/select.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/dcache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/attr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/filesystems.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/sync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fs_struct.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fs_pin.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/nsfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fs_context.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/remap_range.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/block_dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/mpage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/notification.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/mark.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/io_uring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/io-wq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/dax.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/hooks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/bio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/verity/open.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/locks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/drop_caches.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/iomap/apply.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/quota/netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/root.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/array.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/fd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/meminfo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/stat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/page.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/configfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/configfs/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/configfs/item.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/misc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/super.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/kthread.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/control.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/xattr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/acl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/dax.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/util.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/msg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/sem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/shm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/gc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/key.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/process_keys.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/group.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/network.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/audit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/capability.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/task.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/resource.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/net.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/landlock/object.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/landlock/cred.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/landlock/fs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/iint.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_appraise.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/elevator.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-flush.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-settings.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-ioc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-merge.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/genhd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/ioprio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/amiga.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/atari.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/mac.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/msdos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/osf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/sgi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/sun.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/karma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/bsg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-cgroup-rwstat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-throttle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-iocost.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/mq-deadline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-wbt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq-debugfs-zoned.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/keyslot-manager.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/lockref.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/debug_locks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/random32.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/bitmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/scatterlist.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/llist.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/rhashtable.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/refcount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/errseq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/generic-radix-tree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/genalloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/percpu_counter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/iommu-helper.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/syscall.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/irq_poll.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/sbitmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/pldmfw/pldmfw.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/buildid.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/cpumask.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/dump_stack.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/idr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/is_single_threaded.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/klist.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/kobject.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/radix-tree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/show_mem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/vsprintf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/xarray.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/kaslr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/remove.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/console/dummycon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/processor_pdc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/manager.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/support.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/interface.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/misc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/amd/init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/amd/io_pgtable.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/ioasid.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/irq_remapping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/connector/connector.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/dd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/syscore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/security.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/e820.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dax/super.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dax/bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/sync_debug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/loopback.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/linkmode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/bcm84881.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/touchscreen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rtc/class.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rtc/rtc-cmos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/watchdog/watchdog_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/opp/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpuidle/poll_state.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/iscsi_ibft_find.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/efi-bgrt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/memattr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/memmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/secureboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/mokvar-table.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/powercap/dtpm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ras/ras.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ras/cec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/request_sock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/datagram.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/stream.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/scm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/dst.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/neighbour.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/link_watch.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sock_diag.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/flow_offload.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/net-procfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/net-traces.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/selftests.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/dst_cache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/devlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/gro_cells.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sock_map.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethernet/eth.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/cls_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/ematch.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/bitset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/linkmodes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/fec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/stats.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/protocol.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/datagram.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/metrics.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/udp_bpf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/unix/garbage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/unix/scm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_icmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/protocol.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/strparser/strparser.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/options.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/token.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/mib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/syncookies.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/pci/xen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/pci/acpi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
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
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/msr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/bts.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/knc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/suspend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/setup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/p2m.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/xen/efi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/realmode/init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/setup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/quirks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/topology.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/i8253.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/hw_breakpoint.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tsc_msr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/scattered.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/topology.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/rdrand.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/match.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/umwait.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/feat_ctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/tsx.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/intel_epb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/centaur.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/zhaoxin.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/apei.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/cpu/acrn.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/setup_percpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/mpparse.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kgdb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/paravirt-spinlocks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/jailhouse.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/init_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/physaddr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/setup_nx.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pat/memtype.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/srat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/mm/pti.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/panic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/softirq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/resource.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/user.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sys.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/umh.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/pid.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/task_work.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/nsproxy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cred.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/async.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/usermode_driver.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kmod.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/groups.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/loadavg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/clock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/idle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/rt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/wait.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/swait.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/completion.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/topology.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/stop_task.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/autogroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/debug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/cpufreq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/isolation.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/psi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/sched/core_sched.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/process.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/suspend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/handle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/resend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/chip.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/migration.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/dma/mapping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/dma/pool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/entry/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/entry/kvm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kcmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/freezer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/stacktrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/timer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/time/namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/futex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/dma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/uid16.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/acct.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kexec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/cgroup/misc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/utsname.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/audit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/gdbstub.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/hung_task.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/watchdog.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/relay.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/tsacct.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_eprobe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/reuseport_array.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/padata.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/iomem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/rseq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/oom_kill.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/maccess.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmzone.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mm_init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/percpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/workingset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/prfile.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/debug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmap_lock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmu_gather.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mprotect.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mremap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/msync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/vmalloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/process_vm_access.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memblock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/swap_slots.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/frontswap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/sparse.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/kfence/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/kfence/report.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_counter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/cleancache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/zpool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/secretmem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/usercopy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/hmm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/page_reporting.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In mm/bootmem_info.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/open.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/file_table.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/super.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fcntl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/readdir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/select.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/dcache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/attr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/filesystems.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/xattr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/sync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fs_struct.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fs_pin.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/nsfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fs_context.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/remap_range.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/mpage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/notification.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/mark.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/io_uring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/io-wq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/dax.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/hooks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/crypto/bio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/verity/open.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/locks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/drop_caches.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/iomap/iter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/quota/netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/root.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/array.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/fd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/meminfo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/stat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/proc/page.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/configfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/configfs/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/configfs/item.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/misc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/super.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/kthread.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/control.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/xattr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/acl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/fuse/dax.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/util.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/msg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/sem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/shm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/gc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/key.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/process_keys.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/security.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/group.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/network.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/audit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/capability.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/task.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/resource.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/net.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/landlock/object.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/landlock/cred.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/landlock/fs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/iint.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/ima/ima_appraise.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/bdev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/fops.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/elevator.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-flush.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-settings.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-ioc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-merge.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/genhd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/ioprio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/amiga.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/atari.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/mac.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/msdos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/osf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/sgi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/sun.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/karma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/disk-events.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-cgroup-rwstat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-throttle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-iocost.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/mq-deadline.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-wbt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-mq-debugfs-zoned.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/keyslot-manager.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/lockref.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/debug_locks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/random32.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/bitmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/llist.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/rhashtable.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/refcount.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/errseq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/generic-radix-tree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/genalloc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/percpu_counter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/iommu-helper.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/syscall.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/irq_poll.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/ubsan.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/sbitmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/pldmfw/pldmfw.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/buildid.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/cpumask.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/idr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/is_single_threaded.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/klist.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/kobject.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/radix-tree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/show_mem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/vsprintf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In lib/xarray.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/kaslr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/remove.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/console/dummycon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/processor_pdc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/manager.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/support.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/interface.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/misc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/amd/init.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/amd/io_pgtable.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/ioasid.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/irq_remapping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/iommu/iommu-sva-lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/connector/connector.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/dd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/syscore.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/devres.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/memory.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/security.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvdimm/e820.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dax/super.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dax/bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/sync_debug.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/loopback.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/linkmode.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/bcm84881.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/touchscreen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rtc/class.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/rtc/rtc-cmos.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/watchdog/watchdog_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/opp/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/cpuidle/poll_state.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/iscsi_ibft_find.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/efi-bgrt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/memattr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/memmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/secureboot.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/firmware/efi/mokvar-table.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/powercap/dtpm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ras/ras.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/ras/cec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/request_sock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/datagram.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/stream.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/scm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/dev.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/dst.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/neighbour.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/link_watch.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sock_diag.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/flow_offload.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/net-procfs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/net-traces.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/selftests.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/dst_cache.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/devlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/gro_cells.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/sock_map.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethernet/eth.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/cls_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/sched/ematch.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/bitset.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/linkmodes.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/fec.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ethtool/stats.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/protocol.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/datagram.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/metrics.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/udp_bpf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/unix/garbage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/unix/unix_bpf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/unix/scm.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ping.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/proc.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/ip6_icmp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/protocol.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/strparser/strparser.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/options.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/token.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/mib.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/pci/xen.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/pci/acpi.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/kcsan-checks.h:184
Inline: False
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
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/coco/tdx/tdx.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/msr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/bts.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/knc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/p2m.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/ivm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/setup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/quirks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tsc_msr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/scattered.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/topology.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/feat_ctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/tsx.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/centaur.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/zhaoxin.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/mpparse.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kgdb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/paravirt-spinlocks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/jailhouse.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/init_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/physaddr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pat/memtype.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/srat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pti.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/panic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/softirq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/resource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sys.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/umh.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/pid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/task_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/platform-feature.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/nsproxy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cred.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/async.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/usermode_driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kmod.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/groups.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/process.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/suspend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/handle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/resend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/chip.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/irq_sim.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/migration.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/pool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/entry/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/entry/kvm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/module/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kcmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/freezer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/stacktrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/timer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/uid16.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/acct.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kexec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/misc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/utsname.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/audit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/gdbstub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/hung_task.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/watchdog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/relay.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/tsacct.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/pid_list.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_eprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/rethook.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bloom_filter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/reuseport_array.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/padata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/iomem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rseq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/oom_kill.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/maccess.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/folio-compat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmzone.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mm_init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/percpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/workingset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/prfile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/debug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmap_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmu_gather.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mprotect.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mremap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/msync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/vmalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/process_vm_access.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memblock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swap_slots.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/frontswap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/sparse.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/kfence/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/kfence/report.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/migrate_device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_counter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/zpool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/secretmem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/usercopy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hmm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_reporting.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/bootmem_info.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/open.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/file_table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fcntl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/readdir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/select.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/dcache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/attr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/xattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fs_pin.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/nsfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fs_context.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/remap_range.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/mpage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/notification.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/mark.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/dax.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/hooks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/bio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/inline_crypt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/open.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/locks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/drop_caches.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/iomap/iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/quota/netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/root.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/array.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/fd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/meminfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/stat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/page.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/item.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/misc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/kthread.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/control.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/xattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/acl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/dax.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/util.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/msg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/sem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/shm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/gc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/key.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/process_keys.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/security.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/group.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/network.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/audit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/capability.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/task.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/resource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/object.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/cred.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/fs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_appraise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/fops.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/elevator.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-flush.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-settings.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-ioc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-merge.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-stat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/genhd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/amiga.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/atari.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/mac.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/msdos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/osf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/sgi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/sun.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/karma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/disk-events.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-ia-ranges.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-cgroup-rwstat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-cgroup-fc-appid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-throttle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-iocost.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/mq-deadline.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-wbt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-debugfs-zoned.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-crypto-profile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/io_uring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/io-wq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/lockref.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/debug_locks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/bitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/llist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/rhashtable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/refcount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/errseq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/generic-radix-tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/genalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/percpu_counter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/iommu-helper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/syscall.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/irq_poll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/ubsan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/sbitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/pldmfw/pldmfw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/buildid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/cpumask.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/idr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/is_single_threaded.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/klist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/kobject.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/radix-tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/show_mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/vsprintf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/xarray.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpio-mmio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/remove.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/vgaarb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/console/dummycon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/manager.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/support.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/interface.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/misc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/io_pgtable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iommu-sva-lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/connector/connector.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/dd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/syscore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/devres.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/security.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/e820.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dax/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dax/bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/sync_debug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cxl/core/suspend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/ata_piix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/loopback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/linkmode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/bcm84881.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/touchscreen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/class.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/rtc-cmos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/watchdog/watchdog_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/opp/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/amd-pstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpuidle/poll_state.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/iscsi_ibft_find.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/efi-bgrt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/memattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/memmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/secureboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/mokvar-table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ras/ras.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ras/cec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hte/hte.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/request_sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/datagram.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/stream.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/scm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gen_stats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dst.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/neighbour.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/link_watch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock_diag.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/flow_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gro.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net-procfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net-traces.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/selftests.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dst_cache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/devlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gro_cells.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock_map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethernet/eth.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/cls_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/bitset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/linkmodes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/fec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/stats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/protocol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/datagram.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/metrics.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/udp_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/garbage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/unix_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/scm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_icmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/protocol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/strparser/strparser.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/options.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/token.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/pm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/mib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mctp/device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mctp/route.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/pci/acpi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
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
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/coco/tdx/tdx.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/msr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/bts.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/knc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/p2m.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/ivm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/setup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/quirks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tsc_msr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/scattered.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/topology.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/feat_ctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/tsx.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/centaur.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/zhaoxin.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/mpparse.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kgdb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/paravirt-spinlocks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/jailhouse.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/init_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/physaddr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pat/memtype.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/srat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pti.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/memmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/runtime-map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/panic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/softirq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/resource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sys.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/umh.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/pid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/task_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/nsproxy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cred.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/async.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/usermode_driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kmod.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/groups.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/process.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/suspend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/handle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/resend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/chip.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/irq_sim.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/migration.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/direct.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/ops_helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/pool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/entry/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/entry/kvm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/module/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kcmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/freezer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/stacktrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/timer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/uid16.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/acct.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kexec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/misc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/utsname.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/audit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/gdbstub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/hung_task.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/watchdog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/watchdog_hld.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/relay.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/pid_list.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_eprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_synth.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/rethook.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bloom_filter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/memalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cgroup_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_cgrp_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/reuseport_array.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/padata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/context_tracking.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/iomem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rseq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/oom_kill.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/maccess.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/folio-compat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmzone.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mm_init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/percpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/workingset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/prfile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/debug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmap_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmu_gather.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mprotect.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mremap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/msync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/vmalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/process_vm_access.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memblock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swap_slots.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/frontswap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/sparse.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/kfence/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/kfence/report.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory-tiers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/migrate_device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_counter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/zpool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/secretmem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/usercopy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hmm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_reporting.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/bootmem_info.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/open.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/file_table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fcntl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/readdir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/select.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/dcache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/attr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/xattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fs_pin.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/nsfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fs_context.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/remap_range.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/mpage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/notification.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/mark.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/dax.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/hooks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/inline_crypt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/open.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/locks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/drop_caches.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/iomap/iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/quota/netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/root.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/array.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/fd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/meminfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/stat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/page.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/item.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/decompressor_multi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/misc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/control.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/xattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/acl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/dax.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/util.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/msg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/sem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/shm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/gc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/key.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/process_keys.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/security.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/group.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/network.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/audit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/capability.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/task.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/resource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/notify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/safesetid/lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/object.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/cred.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/fs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_appraise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_kexec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/fops.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/elevator.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-flush.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-settings.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-ioc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-merge.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-stat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/genhd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/amiga.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/atari.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/mac.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/msdos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/osf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/sgi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/sun.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/karma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/disk-events.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-ia-ranges.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-cgroup-rwstat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-cgroup-fc-appid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-throttle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-iocost.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/mq-deadline.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-wbt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-debugfs-zoned.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-crypto-profile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/io_uring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/filetable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/openclose.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/uring_cmd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/msg_ring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/timeout.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/fdinfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/tctx.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/poll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/cancel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/rsrc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/rw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/notif.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/io-wq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/lockref.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/debug_locks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/bitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/find_bit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/llist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/rhashtable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/refcount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/errseq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/generic-radix-tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/genalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/percpu_counter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/iommu-helper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/syscall.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/dynamic_debug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/irq_poll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/ubsan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/sbitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/pldmfw/pldmfw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpio-mmio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/remove.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/portdrv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/err.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/vgaarb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/doe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/console/dummycon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/idle/intel_idle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/prmt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/manager.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/support.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/interface.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma/hsu/hsu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/io_pgtable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iommu-sva.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/connector/connector.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/dd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/syscore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/devres.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/security.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/e820.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dax/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dax/bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/sync_debug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cxl/core/suspend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/ata_piix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/loopback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/linkmode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/bcm84881.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/touchscreen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/class.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/rtc-cmos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/watchdog/watchdog_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-io-rewind.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/opp/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/amd-pstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpuidle/governors/haltpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpuidle/poll_state.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/iscsi_ibft_find.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/efi-bgrt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/memattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/memmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/secureboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/mokvar-table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ras/ras.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ras/cec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hte/hte.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/request_sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/datagram.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/stream.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/scm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gen_stats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dst.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/neighbour.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/link_watch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock_diag.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/flow_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gro.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net-procfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net-traces.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/selftests.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dst_cache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/devlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gro_cells.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock_map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethernet/eth.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/cls_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/bitset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/linkmodes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/fec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/stats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/protocol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_ulp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/datagram.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/metrics.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/udp_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/garbage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/unix_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/scm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_icmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/protocol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/strparser/strparser.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/options.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/token.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/pm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/mib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mctp/device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mctp/route.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/pci/acpi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/buildid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/cpumask.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/idr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/is_single_threaded.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/klist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/kobject.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/maple_tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/radix-tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/show_mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/vsprintf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/xarray.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
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
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/coco/tdx/tdx.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/msr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/bts.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/knc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/p2m.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/ivm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/setup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/quirks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tsc_msr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/scattered.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/topology.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/feat_ctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/tsx.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/centaur.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/zhaoxin.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/mpparse.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kgdb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/paravirt-spinlocks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/jailhouse.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/init_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/physaddr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pat/memtype.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/srat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pti.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/memmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/runtime-map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/panic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/softirq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/resource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sys.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/umh.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/pid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/task_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/nsproxy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/notifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cred.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/async.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/usermode_driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/groups.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/vhost_task.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/process.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/suspend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/handle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/resend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/chip.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/irq_sim.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/migration.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/direct.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/ops_helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/pool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/entry/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/entry/kvm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/module/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/module/kmod.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kcmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/freezer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/stacktrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/timer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/uid16.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/acct.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kexec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/misc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/utsname.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/audit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/gdbstub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/hung_task.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/watchdog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/watchdog_perf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/relay.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/pid_list.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_eprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_synth.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/rethook.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_fprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bloom_filter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/memalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cgroup_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_cgrp_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/reuseport_array.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cpumask.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/padata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/context_tracking.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/iomem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rseq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/oom_kill.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/maccess.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/folio-compat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmzone.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mm_init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/percpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/show_mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/workingset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/debug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmap_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmu_gather.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mprotect.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mremap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/msync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/pagewalk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/vmalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/process_vm_access.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memblock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swap_slots.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/frontswap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/sparse.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/kfence/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/kfence/report.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory-tiers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/migrate_device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_counter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/zpool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/secretmem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/usercopy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hmm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_reporting.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/bootmem_info.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/open.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/file_table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fcntl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/readdir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/select.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/dcache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/attr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/xattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fs_pin.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/nsfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fs_context.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/mnt_idmapping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/remap_range.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/mpage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/notification.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/mark.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/dax.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/hooks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/bio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/inline_crypt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/open.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/locks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/iomap/iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/quota/netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/root.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/array.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/fd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/meminfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/stat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/page.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/item.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/block.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/misc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/control.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/xattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/acl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/dax.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/util.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/msg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/sem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/shm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/gc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/key.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/process_keys.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/dh.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/security.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/group.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/network.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/audit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/capability.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/task.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/resource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/notify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/safesetid/lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/object.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/cred.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/fs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_appraise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_kexec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/aead.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/geniv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/skcipher.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/ahash.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/shash.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/akcipher.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/sig.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/kpp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/dh.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/acompress.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/gcm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/rng.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/drbg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/jitterentropy-testing.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/fops.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/elevator.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-flush.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-settings.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-ioc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-merge.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/genhd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/amiga.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/atari.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/mac.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/msdos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/osf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/sgi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/sun.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/karma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/disk-events.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-ia-ranges.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-cgroup-rwstat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-cgroup-fc-appid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-throttle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-iocost.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/mq-deadline.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-wbt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-debugfs-zoned.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-crypto-profile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/io_uring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/filetable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/msg_ring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/timeout.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/fdinfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/tctx.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/poll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/cancel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/kbuf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/rsrc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/rw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/notif.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/io-wq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In rust/helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/lockref.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/debug_locks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/bitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/scatterlist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/find_bit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/llist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/rhashtable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/refcount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/rcuref.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/errseq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/generic-radix-tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/genalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/iommu-helper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/syscall.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/dynamic_debug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/irq_poll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/ubsan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/sbitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/group_cpus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/pldmfw/pldmfw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpio-mmio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/remove.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/portdrv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/err.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/vgaarb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/doe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/console/dummycon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/prmt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/manager.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/support.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/interface.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma/hsu/hsu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/io_pgtable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/perfmon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iommu-sva.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/connector/connector.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/dd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/syscore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/devres.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/security.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/e820.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dax/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dax/bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/sync_debug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cxl/core/suspend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/ata_piix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/loopback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/linkmode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/bcm84881.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/net_failover.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/touchscreen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/class.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/rtc-cmos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/watchdog/watchdog_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-io-rewind.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/opp/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/amd-pstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpuidle/governors/haltpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/iscsi_ibft_find.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/efi-bgrt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/memattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/memmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/secureboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/mokvar-table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/unaccepted_memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hid/bpf/hid_bpf_dispatch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ras/ras.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ras/cec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hte/hte.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/request_sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/datagram.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/stream.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/scm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gen_stats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dst.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/neighbour.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/link_watch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock_diag.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/flow_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gro.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gso.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net-procfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net-traces.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/selftests.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dst_cache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gro_cells.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/failover.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock_map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethernet/eth.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/cls_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/bitset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/linkmodes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/fec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/stats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netfilter/nf_bpf_link.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/protocol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_ulp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/datagram.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/metrics.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/udp_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/garbage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/unix_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/scm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_icmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/protocol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/devlink/leftover.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/devlink/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/devlink/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/devlink/health.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/strparser/strparser.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/options.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/token.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/pm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/mib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mctp/device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mctp/route.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/handshake/netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/handshake/request.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/pci/acpi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/buildid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/cpumask.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/idr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/is_single_threaded.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/klist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/kobject.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/maple_tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/radix-tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/vsprintf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/xarray.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
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
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/coco/tdx/tdx.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/amd/ibs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/msr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/bts.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/knc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/lbr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_nhmex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/p2m.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/multicalls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/xen/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/nested.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/ivm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/idt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/setup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/i8259.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/quirks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tsc_msr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/scattered.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/topology.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/feat_ctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/tsx.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/centaur.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/zhaoxin.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/threshold.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/vmware.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/cpu/debugfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/mpparse.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic_common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/ipi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kprobes/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kgdb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/paravirt-spinlocks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/pvclock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/jailhouse.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/init_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/physaddr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pat/memtype.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/srat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/mm/pti.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/memmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/efi/runtime-map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/panic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/softirq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/resource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/ptrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/signal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sys.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/umh.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/pid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/task_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/nsproxy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/notifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cred.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/reboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/async.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/smpboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/groups.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/vhost_task.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/spinlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/osq_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/locking/qrwlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/process.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/suspend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/printk/nbcon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/printk/printk_ringbuffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/handle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/spurious.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/resend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/chip.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/irq_sim.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/migration.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq/matrix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/direct.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/ops_helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma/pool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/entry/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/entry/kvm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/module/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/module/kmod.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kcmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/freezer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/stacktrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/timer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/tick-broadcast.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/time/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/dma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/uid16.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/acct.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/crash_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kexec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/cgroup/misc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/utsname.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/audit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/gdbstub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/debug/kdb/kdb_debugger.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/hung_task.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/watchdog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/watchdog_perf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/relay.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_clock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/pid_list.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_sched_wakeup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_eprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_synth.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_kdb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/trace_fprobe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/irq_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/task_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bloom_filter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/mprog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/memalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/dispatcher.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/tcx.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cgroup_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_cgrp_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/reuseport_array.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/bpf/cpumask.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/padata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/context_tracking.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/iomem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/rseq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/oom_kill.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/maccess.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/folio-compat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/shrinker.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmzone.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mm_init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/percpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/show_mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/shmem_quota.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/workingset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/debug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmap_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmu_gather.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mprotect.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mremap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/msync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/pagewalk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/vmalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/process_vm_access.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memblock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/swap_slots.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/sparse.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/kfence/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/kfence/report.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory-tiers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/migrate_device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_counter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/zpool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/secretmem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/usercopy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/hmm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/mapping_dirty_helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/page_reporting.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In mm/bootmem_info.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/open.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/file_table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fcntl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/readdir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/select.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/dcache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/attr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/xattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fs_pin.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/nsfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fs_context.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernel_read_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/mnt_idmapping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/remap_range.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/mpage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/notification.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/mark.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/dax.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/hooks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/keysetup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/bio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/crypto/inline_crypt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/open.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/locks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/backing-file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/iomap/iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/quota/netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/root.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/array.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/fd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/meminfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/stat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/namespaces.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/proc/page.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/configfs/item.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/block.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/misc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/control.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/xattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/acl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/fuse/dax.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/tracefs/event_inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/util.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/msg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/sem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/shm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/gc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/key.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/process_keys.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/dh.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/security.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/environ.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/gc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/group.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/network.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/audit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/capability.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/task.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/resource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/af_inet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/apparmor/notify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/safesetid/lsm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/object.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/cred.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/landlock/fs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/platform_certs/machine_keyring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_appraise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_kexec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/ima/ima_efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/aead.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/geniv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/lskcipher.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/skcipher.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/ahash.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/shash.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/akcipher.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/sig.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/kpp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/dh.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/acompress.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/rng.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/drbg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/asymmetric_keys/restrict.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/fops.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/elevator.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-flush.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-ioc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-merge.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/genhd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/amiga.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/atari.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/mac.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/msdos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/osf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/sgi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/sun.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/karma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-rq-qos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/disk-events.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-ia-ranges.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-cgroup-rwstat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-cgroup-fc-appid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-throttle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-iocost.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/mq-deadline.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/bio-integrity.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-wbt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-mq-debugfs-zoned.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In block/blk-crypto-profile.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/io_uring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/filetable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/msg_ring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/timeout.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/tctx.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/poll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/cancel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/rsrc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/rw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/notif.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/waitid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/register.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/io-wq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In io_uring/futex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In rust/helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/lockref.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/debug_locks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/bitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/scatterlist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/find_bit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/llist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/lwq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/percpu-refcount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/rhashtable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/refcount.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/rcuref.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/errseq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/generic-radix-tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/bitmap-str.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/genalloc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/iommu-helper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/syscall.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/dynamic_debug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/closure.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/irq_poll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/stackdepot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/ubsan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/sbitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/group_cpus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/pldmfw/pldmfw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/msr-smp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpio/gpio-mmio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/remove.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/portdrv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/err.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/vgaarb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/doe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/console/dummycon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fb_info.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/tables.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/sleep.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/mipi-disco-img.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/prmt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/manager.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/support.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/interface.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma/hsu/hsu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/pmdomain/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/cpu_hotplug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/events/events_2l.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/xen/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/regulator/event.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_mutex.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_ldsem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/init.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/io_pgtable.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/intel/perfmon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iommufd/iova_bitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/iommu/iommu-sva.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/connector/connector.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/dd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/syscore.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/devres.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/devtmpfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/security.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvdimm/e820.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dax/super.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dax/bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/sync_debug.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cxl/core/suspend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ata/ata_piix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_atomic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_auth.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_client.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_client_modeset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_color_mgmt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_connector.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_drv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_edid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_file.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_framebuffer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_gem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_mm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_mode_object.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_modes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_modeset_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_prime.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_syncobj.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_vblank.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_vblank_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_vma_manager.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_writeback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_debugfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_debugfs_crc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/accel/drm_accel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_gem_shmem_helper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_atomic_helper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_atomic_state_helper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_damage_helper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_flip_work.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_gem_atomic_helper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_gem_framebuffer_helper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_self_refresh_helper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/gpu/drm/drm_fb_helper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/loopback.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/netkit.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/linkmode.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/bcm84881.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/net/net_failover.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/touchscreen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/class.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/rtc/rtc-cmos.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/gov_fair_share.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/gov_step_wise.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/intel/therm_throt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/watchdog/watchdog_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/md/dm-io-rewind.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/opp/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/amd-pstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/cpuidle/governors/haltpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/iscsi_ibft_find.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/efi-bgrt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/memattr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/memmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/cper.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/secureboot.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/mokvar-table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/firmware/efi/unaccepted_memory.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hid/bpf/hid_bpf_dispatch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ras/ras.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ras/debugfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/ras/cec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/hte/hte.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In drivers/dpll/dpll_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/request_sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/datagram.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/stream.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/scm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gen_stats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dst.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/neighbour.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/link_watch.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock_diag.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/flow_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gro.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gso.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net-procfs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/net-traces.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/selftests.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/dst_cache.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/gro_cells.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/failover.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/sock_map.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethernet/eth.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/cls_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/bitset.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/linkmodes.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/fec.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ethtool/stats.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netfilter/nf_bpf_link.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/protocol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_ulp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/datagram.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/metrics.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/fib_rules.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_sigpool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/udp_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv4/tcp_ao.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xfrm/xfrm_state_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/garbage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/unix_bpf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/unix/scm.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ping.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/proc.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_icmp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/protocol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/ip6_offload.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/devlink/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/devlink/dev.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/devlink/param.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/devlink/health.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/devlink/trap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/devlink/rate.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/strparser/strparser.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/options.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/token.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/ctrl.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/mib.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mptcp/sched.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mctp/device.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/mctp/route.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/handshake/alert.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/handshake/netlink.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/handshake/request.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In net/handshake/tlshd.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/pci/acpi.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/buildid.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/dec_and_lock.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/idr.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/is_single_threaded.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/klist.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/kobject.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/maple_tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/nmi_backtrace.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/objpool.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/radix-tree.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/vsprintf.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In lib/xarray.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/kcsan-checks.h:229
Inline: False
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
