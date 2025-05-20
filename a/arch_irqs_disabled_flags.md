# Function: <code>arch_irqs_disabled_flags</code>

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
In init/main.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/softirq.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/params.c (ffffffff8109fb3f)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/irq_work.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In mm/dmapool.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In fs/buffer.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In block/blk-core.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In block/blk-exec.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/utils.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/pci_link.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/dsobject.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/dswstate.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/evgpe.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/evgpeblk.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/evgpeutil.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/evglock.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/evregion.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/evxface.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/exconfig.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/exfldio.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/exnames.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/exoparg3.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/exstorob.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/hwpci.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/hwxface.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/nsalloc.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/nseval.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/nsinit.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/nsnames.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/nsutils.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/nsxfeval.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/nsxfname.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/psutils.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/rscreate.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/rsutils.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/utalloc.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/utcopy.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/uteval.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/utids.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/utmutex.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/utosi.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/utstate.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/utxface.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/xen/manage.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/xen/events/events_2l.c (ffffffff814ca744)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/events/events_fifo.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/base/dma-mapping.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/core/buffer.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/i2c/i2c-core.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In net/core/netpoll.c (0)
Location: arch/x86/include/asm/irqflags.h:151
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
In init/main.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/softirq.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/params.c (ffffffff810a3236)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8115319b)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/irq_work.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In mm/dmapool.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In fs/buffer.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In block/blk-core.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In block/blk-exec.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814c8a2d)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff814c8e8f)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff814d5647)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff814db7c8)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff814dbd64)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff814de988)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff814df04d)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff814df3e3)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff814dfcbc)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff814dff82)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff814e0a8f)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff814e10cc)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff814e1c1b)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff814e28eb)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff814e2f40)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff814e488a)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff814e5624)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff814e6d16)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff814e89ff)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff814e97c9)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff814ea882)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff814eb28b)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nseval.c (ffffffff814ebf03)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff814ec379)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff814ec756)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff814ee53d)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff814ee9a3)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff814ef688)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff814f16ed)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff814f1fd5)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff814f3066)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff814f39ca)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff814f4ca7)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff814f54ee)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff814f5753)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff814f5dd0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff814f6ebc)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff814f71fa)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff814f7d55)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff814f845f)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff814f88cf)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utstate.c (ffffffff814f9105)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff814f95e3)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/xen/manage.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/xen/events/events_2l.c (ffffffff8151b2a4)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/events/events_fifo.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/base/dma-mapping.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/core/buffer.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/i2c/i2c-core.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/irqflags.h:151
Inline: True
```
```
In net/core/netpoll.c (0)
Location: arch/x86/include/asm/irqflags.h:151
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
In init/main.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In arch/x86/xen/suspend.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/softirq.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/params.c (ffffffff810a82f6)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8115d26b)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/irq_work.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In mm/dmapool.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In fs/buffer.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In block/blk-core.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In block/blk-exec.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814ea971)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff814eadd3)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff814f7c79)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff814fe0d7)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff814fe673)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff81501250)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815019b0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff81501d4a)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81502622)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff815028e8)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815033f5)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81503a32)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8150455a)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815052a4)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81505949)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815070de)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff81507e78)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8150956a)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8150b253)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8150c051)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8150d10a)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff8150db13)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nseval.c (ffffffff8150e789)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8150ebff)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff8150f017)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff8150f44a)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81510fa5)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81511433)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815120dd)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff8151414e)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff81514b23)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81515bb4)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81516518)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81517909)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815180dd)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81518316)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81518993)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81519a7f)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81519e15)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8151a971)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8151ae6d)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8151b2dd)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8151bb1c)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff8151c166)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/xen/manage.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/xen/events/events_2l.c (ffffffff81547776)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/events/events_fifo.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/base/dma-mapping.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/usb/core/buffer.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/i2c/i2c-core.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In net/core/netpoll.c (0)
Location: arch/x86/include/asm/irqflags.h:155
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
In init/main.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/softirq.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/params.c (ffffffff810a51d5)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8116029d)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/irq_work.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In mm/dmapool.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In fs/buffer.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In block/blk-core.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In block/blk-exec.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814f67f9)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff814f6e38)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff815068c8)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff8150e59f)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff8150eb4a)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8151172b)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81511e88)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff81512226)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81512b6e)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff81512e34)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81513933)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81513f7b)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81514a9f)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8151586d)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81515f54)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815176c8)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815184ac)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81519b9b)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8151b882)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8151c676)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8151d7dd)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff8151e1bf)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nseval.c (ffffffff8151ee40)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8151f2c9)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff8151f6ef)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff8151fafc)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8152165b)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81521aff)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815225aa)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815248ea)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815253d1)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81526435)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81526d80)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81528126)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81528906)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81528b3e)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815291b4)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8152a2af)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff8152a645)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8152b194)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8152b688)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8152b9e5)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8152c330)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff8152c97c)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/xen/manage.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/xen/events/events_2l.c (ffffffff8155b527)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/events/events_fifo.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/base/dma-mapping.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/usb/core/buffer.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/irqflags.h:155
Inline: True
```
```
In net/core/netpoll.c (0)
Location: arch/x86/include/asm/irqflags.h:155
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
In init/main.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/params.c (ffffffff810ab895)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/power/suspend.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/irq/handle.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8116d35d)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/irq_work.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In mm/dmapool.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In fs/buffer.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In block/blk-core.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In block/blk-exec.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8153760d)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff81537ee2)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff81548a28)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff8154f7a9)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff81552f1a)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff81553d62)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff8155534d)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815590af)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81559dae)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8155a2cc)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8155b240)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff8155b675)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8155c8ce)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff8155d3f0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8155e810)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81560241)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81560b9c)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff81564551)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff81565f5a)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81567e56)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8156b2eb)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8156cbe6)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8156e528)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff8156f78b)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nseval.c (ffffffff81571318)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff81571c19)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815724e8)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81572cfe)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8157577b)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81575f5c)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81576d2e)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff8157a533)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff8157b51e)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff8157d0e6)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff8157e1e6)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff8157f993)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815806aa)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81580ab7)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81581206)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8158337c)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81583991)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81584b85)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815856e6)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81585df0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81586b10)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff815876d7)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81588bef)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81588fe5)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8158a1ce)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8158acdb)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8158c5bf)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8158d759)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/virtio/virtio_ring.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/xen/manage.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/xen/events/events_2l.c (ffffffff815bf851)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/events/events_fifo.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/base/syscore.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/base/dma-mapping.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/usb/core/buffer.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/irqflags.h:159
Inline: True
```
```
In net/core/netpoll.c (0)
Location: arch/x86/include/asm/irqflags.h:159
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
In init/main.c (ffffffff81002818)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/irq.c (ffffffff8101be4b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e4fd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/kernel/ftrace.c (ffffffff81063ee2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/kvm.c (ffffffff8106cd84)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81079717)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush_range
```
```
In kernel/params.c (ffffffff810b24b9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (ffffffff819ecd48)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/idle.c (ffffffff810c4360)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810cd6eb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810d3dd2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810d5e34)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/power/suspend.c (ffffffff810e930e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/handle.c (ffffffff810f62f3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (ffffffff8110652b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff8110caf0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_release
```
```
In kernel/dma/swiotlb.c (ffffffff8110e57b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_free
```
```
In kernel/smp.c (ffffffff8112c793)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/trace/ftrace.c (ffffffff811736fb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (ffffffff8117c3b4)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8118e259)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/irq_work.c (ffffffff811b00b2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In kernel/events/hw_breakpoint.c (ffffffff811e431d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In mm/dmapool.c (ffffffff8125158a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In mm/slub.c (ffffffff812697e9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/buffer.c (ffffffff812d7d1d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In block/blk-core.c (ffffffff814827ab)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_get_request
```
```
In block/blk-exec.c (ffffffff81489c28)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815482cf)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/acpi/osl.c (ffffffff8156d18d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff8156db3a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff8157ea88)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff8158606e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff8158986c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff8158a6b2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff8158bdd1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8158fbca)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815908ae)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff81590e72)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81591dbd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff815921f2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81593476)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81593f8d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815953f5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81596ef8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81597847)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff8159b2a8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8159cc8a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8159eb15)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815a1f48)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815a382e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815a5205)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff815a6466)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nseval.c (ffffffff815a805c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815a881f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815a8d95)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815a9c6b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815ac6f1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815aced1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815adcad)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815b1627)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815b26f8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815b42bc)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815b53c5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff815b6b8b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815b789e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff815b7cab)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815b83e2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff815ba519)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff815bab2e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815bbcf6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815bc89c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff815bcfa5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff815bdcb9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff815be880)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff815bfd6a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff815c016b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff815c1341)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff815c1fd1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff815c38d3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff815c4aa1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/virtio/virtio_ring.c (ffffffff815ea862)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/xen/manage.c (ffffffff815f44c8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff815f5000)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff815f7ccc)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff815f82fd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163ab6b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8164a025)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff81668b48)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__detach_device
  - drivers/iommu/amd_iommu.c:attach_device
```
```
In drivers/base/syscore.c (ffffffff816838c8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/scsi/scsi_lib.c (ffffffff816efc92)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/usb/core/buffer.c (ffffffff81765387)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81778ad8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8178464c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817913ab)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81799884)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a6acf)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3251)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d45f3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd641)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
```
```
In drivers/md/dm-rq.c (ffffffff81816557)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8181f7c9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d412)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/dev.c (ffffffff8189078e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (ffffffff818bf8e6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In init/main.c (ffffffff81002818)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101dd8d)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/irq.c (ffffffff8102606b)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
```
```
In arch/x86/kernel/ftrace.c (ffffffff81069b92)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/kvm.c (ffffffff81072f54)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8107eea8)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In kernel/params.c (ffffffff810bb5e9)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (ffffffff81a27f88)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/idle.c (ffffffff810cd620)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810d5f8e)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810dda72)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810dfd04)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/power/suspend.c (ffffffff810f492e)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/handle.c (ffffffff81101a63)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (ffffffff81112204)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff81117f71)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/smp.c (ffffffff81138063)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/trace/ftrace.c (ffffffff8118134d)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (ffffffff81189bb4)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8119bbe9)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/irq_work.c (ffffffff811be6c2)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In kernel/events/hw_breakpoint.c (ffffffff811f481d)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/slub.c (ffffffff8127e0b8)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/buffer.c (ffffffff812ecd5d)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
```
```
In block/blk-core.c (ffffffff8149d56b)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-exec.c (ffffffff814a3a23)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/acpi/osl.c (ffffffff81584d48)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815856e3)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff815967b8)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff8159e390)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815a1dab)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff815a2c70)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815a43a0)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815a824f)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815a8f36)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815a951d)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815aa45c)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff815aa894)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815abb14)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815ac691)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815adb03)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815af5fc)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815aff4b)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815b379a)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815b51c4)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815b705b)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815bac08)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815bdbc1)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815be36d)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff815bf1ab)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nseval.c (ffffffff815c0eef)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815c16ad)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815c1c3a)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815c2b14)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815c56e8)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815c5ec8)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815c6c9c)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815ca767)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815cb902)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815cd678)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815ce781)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff815cff48)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815d0c61)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff815d106e)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815d17a1)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff815d3973)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff815d3f88)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815d513c)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815d5ce2)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff815d63eb)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff815d7104)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff815d7ce7)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff815d91db)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff815d95cf)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff815da7ba)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff815db457)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff815dcdb6)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff815ddff7)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/xen/manage.c (ffffffff8160f328)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff816100f0)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81612cf0)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8161364d)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
```
In drivers/base/syscore.c (ffffffff816a3598)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/scsi/scsi_lib.c (ffffffff817134f2)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fb773)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184b669)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818593f6)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/dev.c (ffffffff818b10de)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (ffffffff818e8706)
Location: arch/x86/include/asm/irqflags.h:158
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In init/main.c (ffffffff810028e8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101f92b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/irq.c (ffffffff81027d8b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106d442)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/kvm.c (ffffffff81076ae2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8108277d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In kernel/params.c (ffffffff810c1511)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (ffffffff81a98708)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/idle.c (ffffffff810d59fd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810debf0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810e4a73)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810e673c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/power/suspend.c (ffffffff810fcc71)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/handle.c (ffffffff8110a281)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (ffffffff8111baf3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff811222fc)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/smp.c (ffffffff81143203)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/trace/ftrace.c (ffffffff8118e1e9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (ffffffff811971a7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a97f9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/irq_work.c (ffffffff811ce262)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120c52e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/slub.c (ffffffff81299ee8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/buffer.c (ffffffff8130e50d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In block/blk-core.c (ffffffff814cb7ab)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-exec.c (ffffffff814d1c39)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/acpi/osl.c (ffffffff815b5958)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815b60eb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/pci_link.c (ffffffff815c78c8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff815cf72b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff815d1f3f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815d3438)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff815d4310)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815d5aa0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815d99ae)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815da6c5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815dacb8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815dbc36)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff815dc07a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815dd320)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815ddeb7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815df328)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e0e88)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815e17d2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815e52cb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815e6d17)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815e8a40)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815ec7da)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815ef7c8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815eff80)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff815f02fb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff815f0e07)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815f3065)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815f3604)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815f451b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815f6fe3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815f77b5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f8648)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815fbf16)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815fd0b3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815feec9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815fffef)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff816017cf)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81602517)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81602931)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff8160307a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff816052f1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81605907)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81606ad5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81607685)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81607da8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81608ae8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff81609708)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff8160acd8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8160b0e2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8160c2de)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8160cf6b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8160e89c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8160faf7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/xen/manage.c (ffffffff81643128)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81643f56)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81646b12)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff816471e3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
```
In drivers/base/syscore.c (ffffffff816dc4a8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174edda)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183c0d3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f04a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8188e6f9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8189cd3e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/skbuff.c (ffffffff818e8bad)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (ffffffff818fe0ee)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (ffffffff81937f16)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In init/main.c (ffffffff810028e8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102028b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/irq.c (ffffffff8102869b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106e776)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/kvm.c (ffffffff81077b32)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8108383d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In kernel/params.c (ffffffff810c7901)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (ffffffff81ad0058)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/idle.c (ffffffff810e000d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810e9140)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810efc43)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810f1fc9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/power/suspend.c (ffffffff8110905f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/handle.c (ffffffff81116651)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (ffffffff81128266)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
```
```
In kernel/dma/mapping.c (ffffffff8112e932)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/smp.c (ffffffff8114ed43)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/trace/ftrace.c (ffffffff8119a0cd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (ffffffff811a2b87)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b4fe9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/irq_work.c (ffffffff811da882)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff812032f5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/hw_breakpoint.c (ffffffff8121982e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/slub.c (ffffffff812a9da8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/buffer.c (ffffffff8132152d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In block/blk-core.c (ffffffff814e4a6e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-exec.c (ffffffff814eafe3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/acpi/osl.c (ffffffff815d6b88)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815d731b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/pci_link.c (ffffffff815e8ae8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff815f09ab)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff815f31af)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815f46ac)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff815f5588)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815f6d18)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815fac66)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815fba05)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815fbff8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815fcf79)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff815fd3bd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815fe663)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815ff1fa)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8160066b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8160221d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81602b67)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff81606660)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff816080ac)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81609dd5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8160db6f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81610c56)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8161140e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff81611789)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff81612295)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff81614504)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81614aa3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff816159ba)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81618489)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81618c5b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81619aee)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff8161d3c0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff8161e55d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81620373)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81621499)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81622c7a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff816239c2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81623ddc)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81624524)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8162679b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81626db1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81627f70)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81628b20)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81629243)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81629f8d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff8162aba9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff8162c179)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8162c583)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8162d77f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8162e40c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8162fd41)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81630fa0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/xen/manage.c (ffffffff816656c8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81666506)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81668fb2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81669683)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
```
In drivers/base/syscore.c (ffffffff81700538)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/scsi/scsi_lib.c (ffffffff81772fc2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186d9a6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff818709ea)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c1219)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818cf05e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/skbuff.c (ffffffff8191ad0d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (ffffffff8193041e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (ffffffff8196add6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In init/main.c (ffffffff81003908)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810228db)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/irq.c (ffffffff8102a5fb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102fe92)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f153)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d30d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In kernel/params.c (ffffffff810cfb16)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (ffffffff81bc8a75)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/idle.c (ffffffff810e82ba)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In kernel/sched/fair.c (ffffffff810ef28c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/rt.c (ffffffff810f9588)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_lock_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810fd279)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/power/suspend.c (ffffffff81113e69)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/handle.c (ffffffff81122281)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (ffffffff81136a93)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
```
```
In kernel/dma/mapping.c (ffffffff8113d2c5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/smp.c (ffffffff8115f71e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119e261)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
```
```
In kernel/trace/ftrace.c (ffffffff811afcad)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (ffffffff811bb7e7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cddb6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/trace/bpf_trace.c (ffffffff811e9783)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff811f754c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff8122b415)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/hw_breakpoint.c (ffffffff8124566e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/slub.c (ffffffff812db248)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - mm/slub.c:free_partial
```
```
In fs/buffer.c (ffffffff81359ca0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
```
```
In block/blk-exec.c (ffffffff8154ad08)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/acpi/osl.c (ffffffff816808b8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff816810bb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/pci_link.c (ffffffff81694338)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff8169cc4b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff8169ee53)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff816a0735)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff816a1536)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff816a2991)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff816a6d88)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff816a7b28)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff816a8131)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff816a9128)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff816a956c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff816aa376)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff816ab42e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816aca56)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816ae4b1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff816aeebc)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff816b2638)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exnames.c (ffffffff816b43b6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff816b60ed)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff816b9ecd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff816bd069)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff816bda5f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff816bdcc0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff816be7c2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816c0a12)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff816c0fc2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff816c1edb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816c4290)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816c5173)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c5fb1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff816c9949)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff816caabd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff816cc902)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff816cda8f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff816cf2c2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff816d00aa)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff816d04d5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816d0c64)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff816d2f4b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff816d3572)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816d470a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816d53c9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816d5a24)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816d676c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff816d7364)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff816d8961)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d8d74)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816d9f88)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff816dac21)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff816dc720)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816dda07)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/xen/manage.c (ffffffff81714d88)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81715ce0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/xen/events/events_2l.c (ffffffff81719082)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81719beb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
```
In drivers/base/syscore.c (ffffffff817ba628)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/scsi/scsi_lib.c (ffffffff81834c52)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81941fdd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81944ccf)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81994700)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a1a1a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In net/core/skbuff.c (ffffffff819ed2ed)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (ffffffff81a0498e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (ffffffff81a3eb37)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:__netpoll_send_skb
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
In init/main.c (ffffffff810039c6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81022eab)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/irq.c (ffffffff8102af1b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81030ac2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ed83)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d1dd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In kernel/params.c (ffffffff810ca666)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (ffffffff81c41845)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/idle.c (ffffffff810e5ed1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In kernel/sched/fair.c (ffffffff810ed26b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/rt.c (ffffffff810f7885)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_lock_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810fb787)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/power/suspend.c (ffffffff81110b05)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/handle.c (ffffffff8111e264)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (ffffffff811320f3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
```
```
In kernel/dma/mapping.c (ffffffff811379a5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/smp.c (ffffffff8115b6be)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119aff7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffffffff811ad66d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (ffffffff811b93e7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cb296)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/trace/bpf_trace.c (ffffffff811e6b49)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff811f60ac)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81233485)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/hw_breakpoint.c (ffffffff8124fcbe)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/slub.c (ffffffff812e9bc8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - mm/slub.c:free_partial
```
```
In fs/buffer.c (ffffffff81367dd0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
```
```
In block/blk-exec.c (ffffffff81566ac8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/acpi/osl.c (ffffffff8169f3a8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff8169fa0b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/pci_link.c (ffffffff816b1848)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff816b9aab)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff816bc66b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff816bdf4d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff816bed3d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff816c0187)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff816c457e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff816c531e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff816c5916)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff816c69ac)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff816c6df0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff816c7c28)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff816c8d6d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ca395)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816cbdf0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff816cc7f8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff816cff63)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exnames.c (ffffffff816d1c8b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff816d3a01)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exregion.c (ffffffff816d46fb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff816d78c5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff816dac0b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff816db601)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff816dc330)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816de58b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff816deb2a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff816dfa43)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816e22d1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816e31a6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff816e3fd3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff816e796f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff816e8ad2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff816ea919)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff816eba95)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff816ed17c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff816ee0aa)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff816ee4c4)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816eec42)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff816f0f29)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff816f153f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816f26d7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816f3385)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816f39cf)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816f4717)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff816f530a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff816f5d3d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816f6d03)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816f7f06)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff816f8be6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff816fa7c4)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816fbaa5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/xen/manage.c (ffffffff81731978)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81732973)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81c0503c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff817368fa)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/base/syscore.c (ffffffff817cf306)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/scsi/scsi_lib.c (ffffffff81845d22)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8194832d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194ad15)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81997650)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a49cd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In net/core/skbuff.c (ffffffff819ecfb2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (ffffffff81a0570e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (ffffffff81a418d7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:__netpoll_send_skb
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
In init/main.c (ffffffff831b9a10)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/events/core.c (ffffffff81bc4007)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/intel/core.c (ffffffff8100f44d)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/pt.c (ffffffff81018155)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101b452)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810251cb)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102783a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810284fd)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mc_issue
```
```
In arch/x86/xen/irq.c (ffffffff8102bafb)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/xen/multicalls.c (ffffffff8102bc84)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff810317ba)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff81032ad2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81032fc6)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81033212)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810339d0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810345f7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81034763)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff81034d43)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103a007)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/alternative.c (ffffffff8103ea87)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:optimize_nops
```
```
In arch/x86/kernel/tsc.c (ffffffff810409de)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/process.c (ffffffff81041f42)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81042a97)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff831c9c58)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c0e7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104d8f0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810538bb)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054b11)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105a372)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b3d0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:cr4_clear_bits
```
```
In arch/x86/kernel/smp.c (ffffffff8106bd00)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106dab2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/apic.c (ffffffff831d4844)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8107094a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810748ba)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81075688)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81076318)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076980)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076b85)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
```
In arch/x86/kernel/crash.c (ffffffff810792d2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107d326)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
```
```
In arch/x86/kernel/hpet.c (ffffffff8107e6d0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810802b7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_resume
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080acb)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_gs_index
```
```
In arch/x86/kernel/sev.c (ffffffff81084d1f)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_put_ghcb
  - arch/x86/kernel/sev.c:__sev_get_ghcb
```
```
In arch/x86/mm/init.c (ffffffff81bca63b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a732)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8108c61b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:leave_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108dd8d)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e33a8)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff81099902)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b375)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/fork.c (ffffffff810a1480)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/softirq.c (ffffffff810ac008)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
```
```
In kernel/workqueue.c (ffffffff810c7409)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/params.c (ffffffff810cc126)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/kthread.c (ffffffff810cded9)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/core.c (ffffffff81c337b4)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/clock.c (ffffffff810e731b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810e7e91)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In kernel/sched/fair.c (ffffffff810f5274)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/rt.c (ffffffff810f9622)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_lock_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810fdaa6)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/debug.c (ffffffff81105e75)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/locking/spinlock.c (ffffffff81c38aa8)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
```
```
In kernel/power/suspend.c (ffffffff811115b5)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/printk/printk.c (ffffffff8111947a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_safe.c (ffffffff8111c213)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d497)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
```
In kernel/irq/handle.c (ffffffff8111e574)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (ffffffff811345ea)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/rcu/tree.c:rcu_idle_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
```
In kernel/dma/mapping.c (ffffffff81138795)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In kernel/profile.c (ffffffff8113e3ad)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff81153a22)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_update_freq
```
```
In kernel/time/tick-oneshot.c (ffffffff8115596b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/time/tick-oneshot.c:tick_oneshot_mode_active
```
```
In kernel/time/tick-sched.c (ffffffff811568d4)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
```
```
In kernel/smp.c (ffffffff8115c768)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:flush_smp_call_function_from_idle
  - kernel/smp.c:generic_exec_single
```
```
In kernel/stop_machine.c (ffffffff81184418)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/debug_core.c (ffffffff81196b51)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8119978c)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119bf0e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/relay.c (ffffffff811a6fa3)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/tsacct.c (ffffffff811a924e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
```
```
In kernel/trace/trace_clock.c (ffffffff811aa1ef)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff831ec11e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/ring_buffer.c (ffffffff811b573e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811be7c9)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff811c8ec3)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9935)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
```
```
In kernel/trace/trace_hwlat.c (ffffffff811ca721)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_stack.c (ffffffff811cb5ac)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cc5b6)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811cffb8)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
```
In kernel/trace/trace_events.c (ffffffff811d3731)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d6904)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d6b47)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_inject.c (ffffffff811dbd4a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
```
In kernel/trace/bpf_trace.c (ffffffff811e7de9)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec118)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff811f6f9c)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff81219821)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_unlock
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81221b83)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
```
In kernel/bpf/ringbuf.c (ffffffff8122499a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/bpf/stackmap.c (ffffffff81237245)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81250889)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_pmu_snapshot_aux
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_cgroup_switch
```
```
In kernel/events/hw_breakpoint.c (ffffffff8125459e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/filemap.c (ffffffff8125cebe)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In mm/page-writeback.c (ffffffff8126a21e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/swap.c (ffffffff8126fd96)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff81275218)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In mm/shmem.c (ffffffff8127d0fe)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In mm/percpu.c (ffffffff8128a241)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_memcg_free_hook
```
```
In mm/slab_common.c (ffffffff8128e384)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/compaction.c (ffffffff8128eb7b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/compaction.c:compact_lock_irqsave
```
```
In mm/workingset.c (ffffffff81296270)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In mm/gup.c (ffffffff8129aa7e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/memory.c (ffffffff812a2618)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:__pte_alloc
```
```
In mm/page_alloc.c (ffffffff812c4931)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/slub.c (ffffffff812f02f0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff812fd6a0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81304734)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81310d6f)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
```
In fs/buffer.c (ffffffff8136f260)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
```
```
In fs/aio.c (ffffffff8138c577)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:put_reqs_available
```
```
In fs/dax.c (ffffffff813a6c9e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In security/selinux/avc.c (ffffffff814d19ac)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In block/blk-exec.c (ffffffff8156f008)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In lib/irq_poll.c (ffffffff815eb3ad)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/dump_stack.c (ffffffff81be68f9)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff815f11bb)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
  - lib/flex_proportions.c:fprop_new_period
```
```
In lib/ratelimit.c (ffffffff815f7005)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81682058)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff81682a84)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff816939f2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff8169bb1e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff8169eb21)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff816a002d)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff816a0eff)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff816a2209)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff816a6611)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff816a73a0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff816a7998)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff816a89e0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff816a8e24)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff816a9c41)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff816aad51)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ac376)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816addbc)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff816ae7c4)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff816b2229)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff816b3c7d)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff816b59a9)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exregion.c (ffffffff816b6694)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff816b985a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff816bcba8)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff816bd59a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff816be208)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816c0477)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff816c0a16)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff816c192e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816c41c1)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816c507b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c5ea5)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff816c9832)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff816ca997)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff816cc82b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff816cd975)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff816cf17e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff816cff5f)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff816d0379)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816d0af7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff816d2dd1)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff816d33e7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816d4588)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816d5144)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816d586c)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816d65b5)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff816d71a7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff816d8776)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d8b7b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816d9d79)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff816daa5b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff816dc5fb)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816dd8c8)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/acpi/apei/erst.c (ffffffff816ef126)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_write
```
```
In drivers/clk/clk.c (ffffffff816fa12c)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_enable_lock
```
```
In drivers/xen/manage.c (ffffffff81715468)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81716543)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81bf6cba)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a34a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761a72)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
```
```
In drivers/char/random.c (ffffffff8176f366)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_fast_load
```
```
In drivers/char/hpet.c (ffffffff81bfa785)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/base/syscore.c (ffffffff817b2d16)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/clock_ops.c (ffffffff817ccea3)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/scsi/scsi_lib.c (ffffffff81828fc2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff8184ddeb)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/spi/spi.c (ffffffff8186901a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_take_timestamp_post
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d1709)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8190e9b2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192bc8d)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192e855)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81973ea0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197c0f0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819883ad)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819895f0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819a621c)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819ad8ec)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/skbuff.c (ffffffff819d3480)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/dev.c (ffffffff819f21b3)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
```
```
In net/core/netpoll.c (ffffffff81a26397)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/tcp_output.c (ffffffff81ab242e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e0de)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In arch/x86/pci/direct.c (ffffffff8322b2c4)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
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
In init/main.c (ffffffff83299dec)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/events/core.c (ffffffff81c95291)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/intel/core.c (ffffffff81010220)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/pt.c (ffffffff8101bb0e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101ddd0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810296db)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102be17)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102cc0a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mc_issue
```
```
In arch/x86/xen/irq.c (ffffffff8103024e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/xen/multicalls.c (ffffffff81030404)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff832a5acb)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff81037b88)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81038171)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810383b2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038d0c)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81039897)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81039a03)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff81039ac1)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
```
```
In arch/x86/kernel/process_64.c (ffffffff8103a063)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103f9b7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/alternative.c (ffffffff810447f7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:optimize_nops
```
```
In arch/x86/kernel/tsc.c (ffffffff81046ace)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
```
```
In arch/x86/kernel/process.c (ffffffff8104829f)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81048e07)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff832ab068)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81053441)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81055050)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105c0db)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105d461)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810637d4)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
```
In arch/x86/kernel/reboot.c (ffffffff81075f32)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810767e0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/smpboot.c (ffffffff810792bf)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/apic.c (ffffffff832b73d0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c583)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81080d3e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81082b90)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81083921)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81084119)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81084365)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
```
In arch/x86/kernel/crash.c (ffffffff81087332)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/kernel/kgdb.c (ffffffff8108bc46)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
```
```
In arch/x86/kernel/hpet.c (ffffffff8108d319)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8108f127)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_resume
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108fa1b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_gs_index
```
```
In arch/x86/kernel/sev.c (ffffffff81093edf)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_put_ghcb
  - arch/x86/kernel/sev.c:__sev_get_ghcb
```
```
In arch/x86/mm/init.c (ffffffff81c9faba)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/pgtable.c (ffffffff81099cb2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8109be5b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:leave_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d67f)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c6d4b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810a9922)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab4e7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/fork.c (ffffffff810b2898)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In kernel/softirq.c (ffffffff810bdc81)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
```
```
In kernel/workqueue.c (ffffffff810da129)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/params.c (ffffffff810df323)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/kthread.c (ffffffff810e1123)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/core.c (ffffffff810fd839)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:sched_core_unlock
```
```
In kernel/sched/clock.c (ffffffff810fe938)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810ff541)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In kernel/sched/fair.c (ffffffff811116b2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/topology.c (ffffffff8111f353)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/debug.c (ffffffff81124b09)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/spinlock.c (ffffffff81d57388)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
```
```
In kernel/power/suspend.c (ffffffff81131019)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/printk/printk.c (ffffffff8113bcbf)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d7e5)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
```
In kernel/irq/handle.c (ffffffff8113ea11)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (ffffffff81156c97)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/rcu/tree.c:rcu_idle_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
```
In kernel/dma/mapping.c (ffffffff8115b5f5)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In kernel/profile.c (ffffffff811617d8)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff81178112)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_update_freq
```
```
In kernel/time/tick-oneshot.c (ffffffff8117a5db)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/time/tick-oneshot.c:tick_oneshot_mode_active
```
```
In kernel/time/tick-sched.c (ffffffff8117b5f4)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
```
```
In kernel/smp.c (ffffffff81181899)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:flush_smp_call_function_from_idle
  - kernel/smp.c:generic_exec_single
```
```
In kernel/stop_machine.c (ffffffff811ac749)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/debug_core.c (ffffffff811bff84)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811c357b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811c5f57)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
```
```
In kernel/relay.c (ffffffff811d07d4)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/tsacct.c (ffffffff811d2d9e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
```
```
In kernel/trace/trace_clock.c (ffffffff811d3d5f)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff832d0ba6)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/ring_buffer.c (ffffffff811df85e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811e907a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffffffff811f4893)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5405)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f6491)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_stack.c (ffffffff811f7a3c)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f8c17)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811fca8e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
```
In kernel/trace/trace_events.c (ffffffff81200672)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff812037ad)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff81203997)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81207898)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_trigger
```
```
In kernel/trace/trace_eprobe.c (ffffffff81209f5b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_events_inject.c (ffffffff8120b47a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
```
In kernel/trace/bpf_trace.c (ffffffff81218a69)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121d0e8)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (ffffffff8122856c)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In kernel/bpf/syscall.c (ffffffff812317d0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff8124f743)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_unlock_irqrestore
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81259663)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
```
In kernel/bpf/ringbuf.c (ffffffff8125c8da)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/bpf/stackmap.c (ffffffff81271825)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8128b5d7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_cgroup_switch
```
```
In kernel/events/hw_breakpoint.c (ffffffff8129000e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/filemap.c (ffffffff8129966b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In mm/page-writeback.c (ffffffff812a6eb1)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/swap.c (ffffffff812ad102)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff812b2568)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In mm/shmem.c (ffffffff812bb24b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In mm/percpu.c (ffffffff812c95e6)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/slab_common.c (ffffffff812ce2b3)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/compaction.c (ffffffff812cfd30)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/compaction.c:compact_lock_irqsave
```
```
In mm/workingset.c (ffffffff812d6a00)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In mm/gup.c (ffffffff812db42e)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/memory.c (ffffffff812e3988)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:__pte_alloc
```
```
In mm/page_alloc.c (ffffffff81308854)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
```
In mm/slub.c (ffffffff813365fd)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:flush_cpu_slab
  - mm/slub.c:flush_cpu_slab
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
```
```
In mm/kfence/core.c (ffffffff8133bf06)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/huge_memory.c (ffffffff813472d5)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134e469)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8135c044)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:__mem_cgroup_flush_stats
```
```
In fs/buffer.c (ffffffff813c078d)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In fs/aio.c (ffffffff813d9b40)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:put_reqs_available
```
```
In fs/dax.c (ffffffff813f6b5b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In security/selinux/avc.c (ffffffff8152a726)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In block/blk-exec.c (ffffffff815d3648)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In lib/irq_poll.c (ffffffff816578dd)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/dump_stack.c (ffffffff81cdf17a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack_lvl
  - lib/dump_stack.c:dump_stack_lvl
```
```
In lib/flex_proportions.c (ffffffff8165e31d)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
  - lib/flex_proportions.c:fprop_new_period
```
```
In lib/nmi_backtrace.c (ffffffff81662810)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
```
In lib/ratelimit.c (ffffffff81664795)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff816f7188)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff816f7bdc)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff81709822)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff817119d3)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff81715121)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff81716645)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff81717753)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81718b3f)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8171d104)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff8171dfe7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8171e5df)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8171f627)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff8171fa6b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8172089b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff817219ab)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81723093)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81724b7b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81725583)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff817290b7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8172ac46)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8172c9d2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exregion.c (ffffffff8172d6bd)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff817308aa)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81733e1d)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff81734829)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff81735497)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8173772c)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81737ccb)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81738c1b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8173b4f5)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8173c3e0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8173d20a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff81740bd4)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff81741d39)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81743cfb)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81744e45)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff817467ee)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff817475d2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81747a59)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff817481d7)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8174a615)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff8174ac2b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8174be5f)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8174cb6b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8174d293)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8174e121)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff8174ed13)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff8175032a)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8175072f)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8175199d)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff817526f8)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff817545b6)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff817559b8)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/acpi/apei/erst.c (ffffffff81769206)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_write
```
```
In drivers/clk/clk.c (ffffffff8177488c)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_enable_lock
```
```
In drivers/xen/grant-table.c (ffffffff81790e94)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/manage.c (ffffffff81792478)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff817937d3)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff8179856c)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798a1d)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e5ad2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
```
```
In drivers/char/random.c (ffffffff817f4ba3)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_fast_load
```
```
In drivers/char/hpet.c (ffffffff81cfb214)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/base/syscore.c (ffffffff8183c1d5)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/clock_ops.c (ffffffff81857483)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b49a2)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff818db45b)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/spi/spi.c (ffffffff818f9439)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196bcb9)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff819af752)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cee4d)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d1a85)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81a1cba0)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a25350)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a3243d)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81a33b06)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81a535bc)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81a5be4c)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In drivers/hv/hv_common.c (ffffffff81a611f3)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_common_cpu_die
  - drivers/hv/hv_common.c:hv_common_cpu_init
```
```
In net/core/skbuff.c (ffffffff81a831ae)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/dev.c (ffffffff81aa3b13)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
```
```
In net/core/netpoll.c (ffffffff81adb107)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f2ae)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2bce)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In arch/x86/pci/direct.c (ffffffff83315a48)
Location: arch/x86/include/asm/irqflags.h:125
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
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
In init/main.c (ffffffff8100160b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:set_mems_allowed
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/coco/tdx/tdx.c (ffffffff81003a68)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
```
```
In arch/x86/events/core.c (ffffffff81e44549)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/intel/core.c (ffffffff81011835)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:__intel_pmu_snapshot_branch_stack
```
```
In arch/x86/events/intel/pt.c (ffffffff8101dd12)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
```
```
In arch/x86/events/intel/uncore.c (ffffffff81020874)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102e17d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810306b7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8345281e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
```
In arch/x86/xen/irq.c (ffffffff8103583d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/multicalls.c (ffffffff81035e5b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83454b66)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103de21)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8103e43b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e698)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8103f3e3)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_hypercall
  - arch/x86/hyperv/ivm.c:hv_ghcb_hypercall
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103f9e2)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8104076e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff810408f1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff810409b0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff81040b85)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
```
In arch/x86/kernel/traps.c (ffffffff81042664)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81047117)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/ldt.c (ffffffff81048a25)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:switch_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8104cde9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:optimize_nops
```
```
In arch/x86/kernel/tsc.c (ffffffff81050059)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/process.c (ffffffff8105164b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810521c0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81e4990f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105d19e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_clear_bits
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067187)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810699bf)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810704b0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81082043)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/reboot.c (ffffffff81084c40)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8108523c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff81088105)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83468f86)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8108b931)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108ff8f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8109284e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810938de)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81094201)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81094513)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
```
In arch/x86/kernel/crash.c (ffffffff81097270)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/kgdb.c (ffffffff8109c4c3)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
```
```
In arch/x86/kernel/hpet.c (ffffffff8109d6da)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/kernel/kvm.c (ffffffff8109faf0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:kvm_cpu_online
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0cda)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:native_load_gs_index
```
```
In arch/x86/kernel/sev.c (ffffffff810a3cd1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_put_ghcb
  - arch/x86/kernel/sev.c:__sev_get_ghcb
```
```
In arch/x86/mm/init.c (ffffffff81e4f31a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/fault.c (ffffffff810aad35)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/pgtable.c (ffffffff810accc0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810af3dd)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:switch_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0f0e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83479b22)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810bf22e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c1116)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/fork.c (ffffffff810c7ee0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/softirq.c (ffffffff810d4cbb)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
```
```
In kernel/workqueue.c (ffffffff810f18a1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/params.c (ffffffff810f91c7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/kthread.c (ffffffff810f95bd)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/sched/core.c (ffffffff8111a249)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:resched_cpu
```
```
In kernel/sched/fair.c (ffffffff8112d903)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_policy.c (ffffffff81133588)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8114934d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:print_cfs_rq
```
```
In kernel/locking/spinlock.c (ffffffff81f29d5c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
```
```
In kernel/power/suspend.c (ffffffff81152958)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/printk/printk.c (ffffffff8115e7c6)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8115f7ab)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
```
In kernel/irq/irqdesc.c (ffffffff81161ae1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
```
```
In kernel/irq/handle.c (ffffffff8116203a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/manage.c (ffffffff81165469)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
```
```
In kernel/rcu/srcutree.c (ffffffff81175c86)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:spin_lock_irqsave_ssp_contention
  - kernel/rcu/srcutree.c:spin_lock_irqsave_sdp_contention
```
```
In kernel/rcu/tree.c (ffffffff8117d076)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:invoke_rcu_core_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/rcu/tree.c:rcu_idle_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
```
In kernel/dma/mapping.c (ffffffff81185024)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/profile.c (ffffffff811945e3)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff811ad29f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_update_freq
```
```
In kernel/time/tick-oneshot.c (ffffffff811afac7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/time/tick-oneshot.c:tick_oneshot_mode_active
```
```
In kernel/time/tick-sched.c (ffffffff811afe36)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
```
```
In kernel/smp.c (ffffffff811b7f45)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
```
```
In kernel/stop_machine.c (ffffffff811de225)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/debug_core.c (ffffffff811f348e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811f6e5b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811f9206)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/relay.c (ffffffff81204bb9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/tsacct.c (ffffffff8120775c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
```
```
In kernel/trace/trace_clock.c (ffffffff812088c9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff83484c55)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/ring_buffer.c (ffffffff81213626)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff81220d45)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
  - kernel/trace/trace.c:__trace_puts
```
```
In kernel/trace/trace_functions.c (ffffffff8122e5b1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122ec5f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_hwlat.c (ffffffff8122fe90)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_stack.c (ffffffff81231617)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81232540)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812369a9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__blk_trace_note_message
  - kernel/trace/blktrace.c:trace_note_time
```
```
In kernel/trace/trace_events.c (ffffffff8123bf91)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123ed06)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81243737)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff81247568)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff81256dca)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff8126961b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In kernel/bpf/syscall.c (ffffffff81274a5b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff812976b2)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff8129a522)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/percpu_freelist.c (ffffffff812a25f1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
```
In kernel/bpf/ringbuf.c (ffffffff812a6657)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/bpf/stackmap.c (ffffffff812c0944)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff812cc511)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_snapshot_aux
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_cgroup_switch
```
```
In kernel/events/hw_breakpoint.c (ffffffff812e50bc)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/filemap.c (ffffffff812ef653)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/page-writeback.c (ffffffff812fd884)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:mod_lruvec_page_state
```
```
In mm/swap.c (ffffffff81307168)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff8130bb19)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/vmscan.c:count_memcg_events
```
```
In mm/shmem.c (ffffffff81315d73)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/percpu.c (ffffffff81326060)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/slab_common.c (ffffffff8132b9c0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/compaction.c (ffffffff8132e7a8)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/compaction.c:compact_lock_irqsave
```
```
In mm/workingset.c (ffffffff81335c09)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/workingset.c:mod_lruvec_state
```
```
In mm/gup.c (ffffffff8133b010)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/memory.c (ffffffff8133ce9e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/vmalloc.c (ffffffff81360520)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/page_alloc.c (ffffffff81370c42)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
```
In mm/zswap.c (ffffffff8138478e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/slub.c (ffffffff813acdd7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/slub.c:free_partial
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:flush_slab
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:unfreeze_partials
```
```
In mm/kfence/core.c (ffffffff813aeb6d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/huge_memory.c (ffffffff813b9343)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/khugepaged.c (ffffffff813c3733)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/memcontrol.c (ffffffff813d5102)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:consume_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:consume_stock
  - mm/memcontrol.c:__mem_cgroup_flush_stats
  - mm/memcontrol.c:mod_memcg_lruvec_state
  - mm/memcontrol.c:mod_memcg_state
```
```
In fs/buffer.c (ffffffff81443c5c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
```
```
In fs/aio.c (ffffffff814640ef)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:put_reqs_available
```
```
In fs/dax.c (ffffffff81467823)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81591dc6)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
```
In security/selinux/avc.c (ffffffff815c00a1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In block/blk-mq.c (ffffffff816849ac)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
```
```
In lib/irq_poll.c (ffffffff8176f26b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/dump_stack.c (ffffffff81ea5946)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack_lvl
  - lib/dump_stack.c:dump_stack_lvl
```
```
In lib/flex_proportions.c (ffffffff81777a45)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
  - lib/flex_proportions.c:fprop_new_period
```
```
In lib/nmi_backtrace.c (ffffffff8177c63b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
```
In lib/ratelimit.c (ffffffff8177eafe)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - lib/ratelimit.c:___ratelimit
```
```
In lib/vsprintf.c (ffffffff81783b0b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:__ptr_to_hashval
```
```
In drivers/acpi/osl.c (ffffffff81824087)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff81824b66)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff81837c31)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff81840a70)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff81844757)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff81846164)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff818471d1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81848849)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8184d10e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff8184e0af)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8184e6c3)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8184f7a5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff8184fc16)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8185105e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff818518a7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81853564)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff818551b5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81855c7f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff818595a6)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8185b521)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8185d35b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exregion.c (ffffffff8185e08b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff818611ca)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/exstorob.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81864da3)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff81865836)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff818664d7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff81868a04)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81868ff5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff8186a052)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8186cb1f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8186db54)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8186e851)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/nsxfname.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/psutils.c (ffffffff8187256d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff8187374a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81875882)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81876448)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff818785d1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81879602)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81879abc)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff8187a2e5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8187cabe)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff8187d16d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8187e48e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8187f281)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8187fa17)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81880994)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff818816a8)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81882141)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81883044)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/dbconvert.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8188470e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff81885495)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8188756e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81888a51)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/acpi/apei/erst.c (ffffffff8189d8e1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_write
```
```
In drivers/clk/clk.c (ffffffff818aa149)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_enable_lock
```
```
In drivers/xen/grant-table.c (ffffffff818c943e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/manage.c (ffffffff818caca7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/time.c (ffffffff818cb2ee)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu_delta
```
```
In drivers/xen/events/events_base.c (ffffffff818cbc32)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff818d16a8)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d194c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81924ea4)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
```
```
In drivers/char/random.c (ffffffff819353bb)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:crng_make_state
```
```
In drivers/char/hpet.c (ffffffff81ec3720)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/base/syscore.c (ffffffff8197e7d7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/clock_ops.c (ffffffff8199d908)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/scsi/scsi_lib.c (ffffffff819ff931)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2e457)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/spi/spi.c (ffffffff81a4aaad)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac6143)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81b0deee)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b30b84)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b33d5f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81b85d32)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8e5c6)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81b9738b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9e829)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81ba00d4)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81bc27c5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81bcb431)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In drivers/hv/hv_common.c (ffffffff81bd18b1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_common_cpu_die
  - drivers/hv/hv_common.c:hv_common_cpu_init
```
```
In net/core/skbuff.c (ffffffff81bf7ff1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/dev.c (ffffffff81c1c4da)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_reschedule
```
```
In net/core/netpoll.c (ffffffff81c5c5d6)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/tcp_output.c (ffffffff81cfe8ff)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79d47)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In arch/x86/pci/direct.c (ffffffff834d026d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type1
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
In init/main.c (ffffffff81001c02)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:set_mems_allowed
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/coco/tdx/tdx.c (ffffffff810042c5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
```
```
In arch/x86/events/core.c (ffffffff81009ebd)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/intel/core.c (ffffffff81015251)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:__intel_pmu_snapshot_branch_stack
```
```
In arch/x86/events/intel/pt.c (ffffffff81022182)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
```
```
In arch/x86/events/intel/uncore.c (ffffffff810251d4)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103558d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81037cc7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f8d9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
```
In arch/x86/xen/irq.c (ffffffff8103d4cd)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/multicalls.c (ffffffff8103dbec)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83e726e7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff81046c4d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810472ff)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104758f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff81048521)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_hypercall
  - arch/x86/hyperv/ivm.c:hv_ghcb_hypercall
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048abb)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049a2e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81049be8)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff81049cd0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff81049ed5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
```
In arch/x86/kernel/traps.c (ffffffff8104bfe4)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8105134a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/ldt.c (ffffffff81053777)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:switch_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff810591fa)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:optimize_nops
```
```
In arch/x86/kernel/tsc.c (ffffffff8105d438)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/process.c (ffffffff8105ec0a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8105f9b0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810631a0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106acf1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_cpu_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106b5b1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_clear_bits
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810766e7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810796cf)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81080690)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81094a53)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/reboot.c (ffffffff81097c70)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810986b2)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109ba96)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83e8d7dd)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8109fd6e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a4f4f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810a796a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a901f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a983e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810a9e6f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b320d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
```
```
In arch/x86/kernel/hpet.c (ffffffff810b47eb)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/kernel/kvm.c (ffffffff810b7430)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:kvm_cpu_online
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8a5d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:native_load_gs_index
```
```
In arch/x86/kernel/sev.c (ffffffff810bc15a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_put_ghcb
  - arch/x86/kernel/sev.c:__sev_get_ghcb
```
```
In arch/x86/mm/init.c (ffffffff810c0c71)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/fault.c (ffffffff810c4a2e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/pgtable.c (ffffffff810c6daa)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810c981d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:switch_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb63e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
```
```
In arch/x86/mm/kmmio.c (ffffffff810d24d6)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea3ead)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810daf7d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ddaaa)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/fork.c (ffffffff810e50aa)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/exit.c (ffffffff810f1fa7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810f3cc5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
```
```
In kernel/workqueue.c (ffffffff81114867)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/params.c (ffffffff8111bd45)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/kthread.c (ffffffff8111c1ed)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/sched/core.c (ffffffff811419b0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:sched_core_unlock
```
```
In kernel/sched/fair.c (ffffffff811576e8)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_policy.c (ffffffff8115d965)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff81177c5b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:print_cfs_rq
```
```
In kernel/locking/spinlock.c (ffffffff820d5c8c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
```
```
In kernel/power/suspend.c (ffffffff81181c64)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/printk/printk.c (ffffffff811916fb)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81192b0b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
```
In kernel/irq/irqdesc.c (ffffffff811952b7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
```
```
In kernel/irq/handle.c (ffffffff81195aaa)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/manage.c (ffffffff8119935c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
```
```
In kernel/rcu/srcutree.c (ffffffff811acb57)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:spin_lock_irqsave_ssp_contention
  - kernel/rcu/srcutree.c:spin_lock_irqsave_sdp_contention
```
```
In kernel/rcu/tree.c (ffffffff811b694b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:invoke_rcu_core_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
```
```
In kernel/dma/mapping.c (ffffffff811c07b0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/profile.c (ffffffff811d1d53)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff811ed7c6)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_update_freq
```
```
In kernel/time/tick-oneshot.c (ffffffff811f04a9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/time/tick-oneshot.c:tick_oneshot_mode_active
```
```
In kernel/time/tick-sched.c (ffffffff811f088c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
```
```
In kernel/smp.c (ffffffff811f91e9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
```
```
In kernel/stop_machine.c (ffffffff81223d55)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/debug_core.c (ffffffff8123a2c9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8123e101)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81240706)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/relay.c (ffffffff8124c8eb)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/tsacct.c (ffffffff8124fb12)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
```
```
In kernel/trace/trace_clock.c (ffffffff81250dd9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff83eb343c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/ring_buffer.c (ffffffff8125cdf5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8126bbe2)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
  - kernel/trace/trace.c:__trace_puts
```
```
In kernel/trace/trace_functions.c (ffffffff8127a4de)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127ac7c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127c08d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_stack.c (ffffffff8127dbb9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127ec30)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff8128368e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__blk_trace_note_message
  - kernel/trace/blktrace.c:trace_note_time
```
```
In kernel/trace/trace_events.c (ffffffff8128873e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128c753)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812912b4)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff81295bd5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff812a6c39)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff812be4ce)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In kernel/bpf/syscall.c (ffffffff812c67be)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put
```
```
In kernel/bpf/helpers.c (ffffffff812f2532)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff812f66a2)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81300085)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
```
In kernel/bpf/ringbuf.c (ffffffff813048ab)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/bpf/memalloc.c (ffffffff8131b9d8)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:unit_alloc
```
```
In kernel/bpf/offload.c (ffffffff813217d9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff813241e7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff813363f9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_pmu_snapshot_aux
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134e8fc)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In kernel/context_tracking.c (ffffffff81355c0e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_irq_exit_irqson
  - kernel/context_tracking.c:ct_irq_enter_irqson
  - kernel/context_tracking.c:ct_idle_exit
```
```
In mm/filemap.c (ffffffff8135a049)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/page-writeback.c (ffffffff813676e4)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:mod_lruvec_page_state
```
```
In mm/swap.c (ffffffff81370c5a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff8137638b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/vmscan.c:count_memcg_events
```
```
In mm/shmem.c (ffffffff81389e89)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/percpu.c (ffffffff8139ae3a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/slab_common.c (ffffffff813a0d1a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/compaction.c (ffffffff813a4f8d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/compaction.c:compact_lock_irqsave
```
```
In mm/workingset.c (ffffffff813ac9eb)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/workingset.c:mod_lruvec_state
```
```
In mm/gup.c (ffffffff813b2c62)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/memory.c (ffffffff813b4aba)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/vmalloc.c (ffffffff813dc0fa)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/zswap.c (ffffffff814023aa)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/slub.c (ffffffff8142cddd)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/slub.c:free_partial
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:flush_slab
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:unfreeze_partials
```
```
In mm/kfence/core.c (ffffffff8142f0be)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/huge_memory.c (ffffffff8143b5f9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/khugepaged.c (ffffffff81446119)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In mm/memcontrol.c (ffffffff8145ab8a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:consume_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:consume_stock
  - mm/memcontrol.c:__mem_cgroup_flush_stats
  - mm/memcontrol.c:mod_memcg_lruvec_state
  - mm/memcontrol.c:mod_memcg_state
```
```
In fs/buffer.c (ffffffff814d30f5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
```
```
In fs/aio.c (ffffffff814f43ff)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:put_reqs_available
```
```
In fs/dax.c (ffffffff814f7ec9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81639706)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
```
In ipc/util.c (ffffffff8163c67e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In security/selinux/avc.c (ffffffff8166c5c1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d121b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In block/bio.c (ffffffff8172df6e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_alloc_irq_cache_splice
```
```
In block/blk-mq.c (ffffffff81742d3c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
```
```
In lib/rhashtable.c (ffffffff817da3cc)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8189ec5f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_complete
  - lib/irq_poll.c:irq_poll_sched
```
```
In drivers/acpi/osl.c (ffffffff81955437)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff81956f2b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff8196cf01)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff819774b5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff8197c298)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff8197db52)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff8197efc1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81981269)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff819860c1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81986f04)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff81988153)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81989126)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff819895fc)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8198ae41)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff8198c0b0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8198db46)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8198fc9d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81990db1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff81995784)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8199781f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81999bcf)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff8199a9d7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8199e4fb)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff819a2d4c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff819a3950)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff819a49d9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff819a76dd)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff819a855e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff819a912f)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff819acddf)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff819ae11c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff819aeed7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff819b3410)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff819b49c6)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff819b712a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff819b880a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff819baac3)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff819bbd2d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff819bc52d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff819bd879)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
```
```
In drivers/acpi/acpica/uteval.c (ffffffff819c00e6)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff819c0ef7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff819c21ca)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/utobject.c (ffffffff819c314e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff819c3c05)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utstate.c (ffffffff819c4e8b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff819c60bf)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff819c7e36)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff819c83c3)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff819ca8b6)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff819cacf5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff819cd681)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff819cf026)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/acpi/apei/erst.c (ffffffff819e66de)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_write
```
```
In drivers/clk/clk.c (ffffffff819f51d9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_enable_lock
```
```
In drivers/xen/grant-table.c (ffffffff81a1a2ae)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/manage.c (ffffffff81a1be6a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/time.c (ffffffff81a1c5b5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu_delta
```
```
In drivers/xen/events/events_base.c (ffffffff81a1d042)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81a23027)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a2372c)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a817e4)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
```
```
In drivers/char/random.c (ffffffff81a93c7d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u16
  - drivers/char/random.c:get_random_u8
  - drivers/char/random.c:crng_make_state
```
```
In drivers/char/hpet.c (ffffffff81a9a1bd)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/base/syscore.c (ffffffff81aebdae)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/clock_ops.c (ffffffff81b0f055)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7df84)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81baf6a7)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/spi/spi.c (ffffffff81bd189d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c50273)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81c9dfe0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc54b4)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc8d0e)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d24f85)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2e8ff)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d381fe)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3fdbc)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d41cf9)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81d674d1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d74c6b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In drivers/hv/hv_common.c (ffffffff81d7d3e1)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_common_cpu_die
  - drivers/hv/hv_common.c:hv_common_cpu_init
```
```
In net/core/skbuff.c (ffffffff81da6da5)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/dev.c (ffffffff81dcd4ed)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_reschedule
```
```
In net/core/xdp.c (ffffffff81e064ce)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e12cc6)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/netlink/af_netlink.c (ffffffff81e69c7b)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3819)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a782)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f2067a)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33307)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46b57)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ioam6.c (ffffffff81fa9970)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae28d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbea64)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
```
```
In arch/x86/pci/direct.c (ffffffff83f14102)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type1
```
```
In lib/dump_stack.c (ffffffff8201fddc)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack_lvl
  - lib/dump_stack.c:dump_stack_lvl
```
```
In lib/nmi_backtrace.c (ffffffff8203908d)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
```
In lib/ratelimit.c (ffffffff8203b762)
Location: arch/x86/include/asm/irqflags.h:123
Inline: True
Inline callers:
  - lib/ratelimit.c:___ratelimit
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
In init/main.c (ffffffff810019c5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:set_mems_allowed
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/coco/tdx/tdx.c (ffffffff81003a30)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
```
```
In arch/x86/events/core.c (ffffffff810096d3)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/intel/core.c (ffffffff81014ab4)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:__intel_pmu_snapshot_branch_stack
```
```
In arch/x86/events/intel/pt.c (ffffffff81021e72)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
```
```
In arch/x86/events/intel/uncore.c (ffffffff810250c4)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103550d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81037c27)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83690a69)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
```
In arch/x86/xen/irq.c (ffffffff8103d35d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/multicalls.c (ffffffff8103da8c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83693607)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff81046eb2)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8104767f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104790f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff810488cd)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_hypercall
  - arch/x86/hyperv/ivm.c:hv_ghcb_hypercall
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048da4)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049c5e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81049e18)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff81049f00)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a4f5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
```
In arch/x86/kernel/traps.c (ffffffff8104c855)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810520aa)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/ldt.c (ffffffff81054757)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:switch_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8105a7a8)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/tsc.c (ffffffff8105e9f0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/process.c (ffffffff810602fa)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81061100)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064af0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c661)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_cpu_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106cf61)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_clear_bits
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078967)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107b97f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81082ad7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810979f3)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/reboot.c (ffffffff8109ad10)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8109b93a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/apic/apic.c (ffffffff836b107d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a2cf6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a8035)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810aabcb)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810ac23f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810aca57)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810ad22f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b630d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
```
```
In arch/x86/kernel/hpet.c (ffffffff810b78c9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/kernel/kvm.c (ffffffff810ba620)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:kvm_cpu_online
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bbc2d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/kernel/sev.c (ffffffff810bf464)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:__set_pages_state
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_put_ghcb
  - arch/x86/kernel/sev.c:__sev_get_ghcb
```
```
In arch/x86/mm/init.c (ffffffff810c4351)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/fault.c (ffffffff810c826e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/pgtable.c (ffffffff810ca4fa)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810cce9d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:switch_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cec5e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
```
```
In arch/x86/mm/kmmio.c (ffffffff810d5946)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c816c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810e650d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8f94)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/fork.c (ffffffff810f074a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/exit.c (ffffffff810fdf27)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff811000f5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
```
```
In kernel/workqueue.c (ffffffff811207f7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/params.c (ffffffff81128f95)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/kthread.c (ffffffff8112943d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/sched/core.c (ffffffff8115248c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:sched_mm_cid_remote_clear
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:sched_core_unlock
```
```
In kernel/sched/fair.c (ffffffff81167716)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:destroy_cfs_bandwidth
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_policy.c (ffffffff8116e088)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff811888d4)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:print_cfs_rq
```
```
In kernel/locking/spinlock.c (ffffffff8215906c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
```
```
In kernel/power/suspend.c (ffffffff81192b44)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/printk/printk.c (ffffffff811a15f2)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_emit_next_record
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a436b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
```
In kernel/irq/irqdesc.c (ffffffff811a6c47)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
```
```
In kernel/irq/handle.c (ffffffff811a747a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/manage.c (ffffffff811ab03c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
```
```
In kernel/rcu/srcutree.c (ffffffff811be9d6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:spin_lock_irqsave_ssp_contention
  - kernel/rcu/srcutree.c:spin_lock_irqsave_sdp_contention
```
```
In kernel/rcu/tree.c (ffffffff811c737b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:synchronize_rcu
  - kernel/rcu/tree.c:invoke_rcu_core_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
```
```
In kernel/dma/mapping.c (ffffffff811d32a0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/profile.c (ffffffff811e6313)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff81201ef6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_update_freq
```
```
In kernel/time/tick-oneshot.c (ffffffff81204c09)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/time/tick-oneshot.c:tick_oneshot_mode_active
```
```
In kernel/time/tick-sched.c (ffffffff812052ac)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
```
```
In kernel/smp.c (ffffffff8120de0f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
```
```
In kernel/stop_machine.c (ffffffff8123a3b5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/debug_core.c (ffffffff812512d9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81255156)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81257796)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/relay.c (ffffffff81263c52)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/tsacct.c (ffffffff81266ec2)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
```
```
In kernel/trace/trace_clock.c (ffffffff81268159)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff836d86fc)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/ring_buffer.c (ffffffff81273de5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff81282f42)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
  - kernel/trace/trace.c:__trace_array_puts
```
```
In kernel/trace/trace_functions.c (ffffffff81291f8e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8129279c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_hwlat.c (ffffffff81293bad)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_osnoise.c (ffffffff812963ff)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
```
```
In kernel/trace/trace_stack.c (ffffffff8129a639)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129b7c0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812a033a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__blk_trace_note_message
  - kernel/trace/blktrace.c:trace_note_time
```
```
In kernel/trace/trace_events.c (ffffffff812a546e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a9653)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812ae524)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff812b2ae5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8cf9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff812e510e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In kernel/bpf/syscall.c (ffffffff812edac7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put
```
```
In kernel/bpf/helpers.c (ffffffff8131f0b2)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff81324572)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8132ebe5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
```
In kernel/bpf/ringbuf.c (ffffffff81333253)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/bpf/memalloc.c (ffffffff8134b418)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:unit_alloc
```
```
In kernel/bpf/offload.c (ffffffff813512cb)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81354427)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81367139)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_pmu_snapshot_aux
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137fa8c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In kernel/context_tracking.c (ffffffff8138729e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_irq_exit_irqson
  - kernel/context_tracking.c:ct_irq_enter_irqson
  - kernel/context_tracking.c:ct_idle_exit
```
```
In mm/filemap.c (ffffffff8138ba99)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/page-writeback.c (ffffffff81399b84)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:mod_lruvec_page_state
```
```
In mm/swap.c (ffffffff813a2e3a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff813a5c9b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/vmscan.c:count_memcg_events
```
```
In mm/shmem.c (ffffffff813bc069)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/percpu.c (ffffffff813cdefa)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/slab_common.c (ffffffff813d3f9a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/compaction.c (ffffffff813d84fd)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/compaction.c:compact_lock_irqsave
```
```
In mm/workingset.c (ffffffff813e0d8b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/workingset.c:mod_lruvec_state
```
```
In mm/gup.c (ffffffff813e78d2)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/memory.c (ffffffff813e971a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/vmalloc.c (ffffffff81410b1a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/page_alloc.c (ffffffff81422af7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/zswap.c (ffffffff8143526a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/slub.c (ffffffff814623ed)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/slub.c:free_partial
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:flush_slab
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:unfreeze_partials
```
```
In mm/kfence/core.c (ffffffff81464dcb)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/huge_memory.c (ffffffff81470f69)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/khugepaged.c (ffffffff8147b7f9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/memcontrol.c (ffffffff814907ea)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:consume_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:consume_stock
  - mm/memcontrol.c:mod_memcg_lruvec_state
  - mm/memcontrol.c:mod_memcg_state
```
```
In fs/buffer.c (ffffffff81509fb5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
```
```
In fs/aio.c (ffffffff8152b1d1)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:put_reqs_available
```
```
In fs/dax.c (ffffffff8152f0c9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81671bf9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
```
In ipc/util.c (ffffffff81674a83)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In security/selinux/avc.c (ffffffff816a48f5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a12b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In block/bio.c (ffffffff8176a1ae)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_alloc_irq_cache_splice
```
```
In block/blk-mq.c (ffffffff81780532)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
```
```
In lib/rhashtable.c (ffffffff818196d8)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/percpu_counter.c (ffffffff818ce005)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_add_batch
```
```
In lib/irq_poll.c (ffffffff818e122f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_complete
  - lib/irq_poll.c:irq_poll_sched
```
```
In drivers/acpi/osl.c (ffffffff8199b837)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff8199d340)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff819b3491)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff819bdea0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff819c2d38)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff819c4602)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff819c5a73)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff819c7cc7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff819ccaf1)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff819cd941)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff819ceb93)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff819cfb66)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff819d003c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff819d18c1)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff819d2b30)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff819d45d6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff819d673d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff819d78b1)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff819dc3a7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff819de49f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff819e09b6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff819e1765)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff819e51cb)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff819e99fc)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff819ea600)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff819eb6a9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff819ee3fd)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff819ef250)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff819effdf)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff819f3cae)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff819f4fdc)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff819f5dc7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff819fa310)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff819fb9c6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff819fe27a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff819ff96c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81a01c55)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81a02ecd)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81a036cd)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81a04a69)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81a072e6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81a08247)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81a0951a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81a0a4ee)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81a0afb9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81a0c28b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff81a0d4bf)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81a0f23a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a0f7e3)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81a11d16)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff81a1215e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff81a14b15)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81a164f6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/acpi/apei/erst.c (ffffffff81a2ed7e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_write
```
```
In drivers/clk/clk.c (ffffffff81a3d959)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_enable_lock
```
```
In drivers/xen/grant-table.c (ffffffff81a6368e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/manage.c (ffffffff81a6500a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/time.c (ffffffff81a65755)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu_delta
```
```
In drivers/xen/events/events_base.c (ffffffff81a66248)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81a6c3e9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6cbdf)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81accdd4)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
```
```
In drivers/char/random.c (ffffffff81adf76d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u16
  - drivers/char/random.c:get_random_u8
  - drivers/char/random.c:crng_make_state
```
```
In drivers/char/hpet.c (ffffffff81ae5a2d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/base/syscore.c (ffffffff81b39fee)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/clock_ops.c (ffffffff81b5d105)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd1d64)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81c06390)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/spi/spi.c (ffffffff81c28378)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_take_timestamp_post
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb7823)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81d05350)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2d144)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d30a1e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e1a5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d97a0f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81da25fe)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81daa92c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8214235a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81dd25e1)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de2bb2)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In drivers/hv/hv_common.c (ffffffff81deb658)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_common_cpu_init
```
```
In net/core/skbuff.c (ffffffff81e15ff7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/dev.c (ffffffff81e3e054)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:dev_kfree_skb_any_reason
  - net/core/dev.c:dev_kfree_skb_irq_reason
  - net/core/dev.c:__netif_reschedule
```
```
In net/core/xdp.c (ffffffff81e78d3b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e865e6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/netlink/af_netlink.c (ffffffff81ec5c10)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81f21a59)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a2b2)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80151)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92671)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6497)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ioam6.c (ffffffff8200a2f2)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e9e5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f9f3)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/handshake/request.c (ffffffff82092d27)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/pci/direct.c (ffffffff8373a882)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type1
```
```
In lib/dump_stack.c (ffffffff8209fcec)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack_lvl
  - lib/dump_stack.c:dump_stack_lvl
```
```
In lib/nmi_backtrace.c (ffffffff820b739d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
```
In lib/ratelimit.c (ffffffff820b9c42)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/ratelimit.c:___ratelimit
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
In init/main.c (ffffffff810019d8)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:set_mems_allowed
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/coco/tdx/tdx.c (ffffffff81003d60)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
```
```
In arch/x86/events/core.c (ffffffff8100edf3)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/intel/core.c (ffffffff81019aa4)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:__intel_pmu_snapshot_branch_stack
```
```
In arch/x86/events/intel/pt.c (ffffffff81028022)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102b224)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103b70d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103d84f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/enlighten_pv.c:xen_start_context_switch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c0539)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
```
In arch/x86/xen/irq.c (ffffffff8104381d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/multicalls.c (ffffffff81043f4c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff838c3154)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104d5da)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8104ddb6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e18d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104f94b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_hypercall
  - arch/x86/hyperv/ivm.c:hv_ghcb_hypercall
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8105002e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050ef8)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81051078)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff81051160)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff81051755)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
```
In arch/x86/kernel/traps.c (ffffffff81053ad5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810592ca)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
```
In arch/x86/kernel/ldt.c (ffffffff8105b997)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:switch_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff81061a80)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:optimize_nops_inplace
```
```
In arch/x86/kernel/tsc.c (ffffffff81065aa0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/process.c (ffffffff8106737a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81068210)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106bf80)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810738b1)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_cpu_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81074731)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_clear_bits
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107fe17)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81082edf)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8108a5e7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109ef63)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/smp.c (ffffffff810a2f44)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/apic/apic.c (ffffffff838e1658)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a9b9c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810af0c4)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810b1ba6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2fde)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b36d7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810b3daf)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
```
In arch/x86/kernel/kgdb.c (ffffffff810bd74d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
```
```
In arch/x86/kernel/hpet.c (ffffffff810bed09)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/kernel/kvm.c (ffffffff810c1a60)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:kvm_cpu_online
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2b10)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff810c67b4)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:__set_pages_state
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_put_ghcb
  - arch/x86/kernel/sev.c:__sev_get_ghcb
```
```
In arch/x86/mm/init.c (ffffffff810cc7a1)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/fault.c (ffffffff810d071c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/pgtable.c (ffffffff810d286a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810d556d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:switch_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d733e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
```
```
In arch/x86/mm/kmmio.c (ffffffff810de146)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8d6c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810ee88d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f11d4)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/fork.c (ffffffff810f9aaa)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/exit.c (ffffffff81106bd7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81109815)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
```
```
In kernel/workqueue.c (ffffffff81129187)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/params.c (ffffffff81133615)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/kthread.c (ffffffff81133abd)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/sched/core.c (ffffffff8115e351)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:sched_mm_cid_remote_clear
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:sched_core_unlock
```
```
In kernel/sched/fair.c (ffffffff8117450f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:destroy_cfs_bandwidth
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_policy.c (ffffffff8118280e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:vtime_init_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff811971b4)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:print_cfs_rq
```
```
In kernel/locking/spinlock.c (ffffffff8223c8ec)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
```
```
In kernel/power/suspend.c (ffffffff811a1534)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/printk/printk.c (ffffffff811b1d12)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_emit_next_record
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b3e5b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
```
In kernel/irq/irqdesc.c (ffffffff811b6767)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
```
```
In kernel/irq/handle.c (ffffffff811b6fda)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/manage.c (ffffffff811bac7c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
```
```
In kernel/rcu/update.c (ffffffff811cd499)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811ceef6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:spin_lock_irqsave_ssp_contention
  - kernel/rcu/srcutree.c:spin_lock_irqsave_sdp_contention
```
```
In kernel/rcu/tree.c (ffffffff811d789b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_nocb_rdp_offload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rdp_offload_toggle
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:synchronize_rcu
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:invoke_rcu_core_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_report_qs_rdp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
```
```
In kernel/dma/mapping.c (ffffffff811e7f20)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/profile.c (ffffffff811fc063)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff81218396)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_update_freq
```
```
In kernel/time/tick-oneshot.c (ffffffff8121b1c9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/time/tick-oneshot.c:tick_oneshot_mode_active
```
```
In kernel/time/tick-sched.c (ffffffff8121b97c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
```
```
In kernel/smp.c (ffffffff8122559f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
```
```
In kernel/stop_machine.c (ffffffff81254085)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/debug_core.c (ffffffff8126b129)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8126efd6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81271656)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/watchdog.c (ffffffff812784fc)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
```
```
In kernel/relay.c (ffffffff8127da42)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/tsacct.c (ffffffff81280e41)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
```
```
In kernel/trace/trace_clock.c (ffffffff812823c9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffffffff8390ac8c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/ring_buffer.c (ffffffff8128e403)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8129e2d2)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
  - kernel/trace/trace.c:__trace_array_puts
```
```
In kernel/trace/trace_functions.c (ffffffff812ad59e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ade82)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_hwlat.c (ffffffff812af20d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b1a6b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
```
```
In kernel/trace/trace_stack.c (ffffffff812b5cb9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b6e70)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812bba6a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__blk_trace_note_message
  - kernel/trace/blktrace.c:trace_note_time
```
```
In kernel/trace/trace_events.c (ffffffff812c0e8e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c5363)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812caa44)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff812cf095)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff812e5cc9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff813031be)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In kernel/bpf/syscall.c (ffffffff8130c677)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put
```
```
In kernel/bpf/helpers.c (ffffffff813414eb)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff813497c2)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_new
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/hashtab.c (ffffffff8134f15c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lock_bucket
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81353105)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff81357292)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_push_elem
  - kernel/bpf/queue_stack_maps.c:__stack_map_get
  - kernel/bpf/queue_stack_maps.c:__queue_map_get
```
```
In kernel/bpf/ringbuf.c (ffffffff81357943)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve
```
```
In kernel/bpf/memalloc.c (ffffffff81371de8)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free_rcu
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:unit_alloc
```
```
In kernel/bpf/offload.c (ffffffff8137872b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff8137cd97)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff813902a9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_pmu_snapshot_aux
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a8c9c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In kernel/context_tracking.c (ffffffff813b0cde)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_irq_exit_irqson
  - kernel/context_tracking.c:ct_irq_enter_irqson
  - kernel/context_tracking.c:ct_idle_exit
```
```
In mm/filemap.c (ffffffff813b5609)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/page-writeback.c (ffffffff813c3984)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:lruvec_stat_mod_folio
```
```
In mm/swap.c (ffffffff813ccaba)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff813cf80b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/vmscan.c:count_memcg_events
```
```
In mm/shmem.c (ffffffff813e6c59)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/percpu.c (ffffffff813f886a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/compaction.c (ffffffff814021dd)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/compaction.c:compact_lock_irqsave
```
```
In mm/workingset.c (ffffffff8140b65b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/workingset.c:mod_lruvec_state
```
```
In mm/gup.c (ffffffff81412542)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/memory.c (ffffffff8141469a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff814357da)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/vmalloc.c (ffffffff8143d47a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/slub.c (ffffffff8145e92d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/slub.c:free_partial
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:flush_slab
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:put_partials
```
```
In mm/page_io.c (ffffffff81463059)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/zswap.c (ffffffff8146e30a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/kfence/core.c (ffffffff81493a1b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/huge_memory.c (ffffffff814a0629)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/khugepaged.c (ffffffff814aaad9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In mm/memcontrol.c (ffffffff814c00c7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:consume_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:consume_stock
  - mm/memcontrol.c:mod_memcg_lruvec_state
  - mm/memcontrol.c:mod_memcg_state
```
```
In fs/buffer.c (ffffffff8153ee75)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
```
```
In fs/aio.c (ffffffff815600a1)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:put_reqs_available
```
```
In fs/dax.c (ffffffff81563fa9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In fs/pstore/platform.c (ffffffff816adacc)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
```
In ipc/util.c (ffffffff816b0e43)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In security/selinux/avc.c (ffffffff816e1355)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747c2b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In block/bio.c (ffffffff817ac45e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_alloc_irq_cache_splice
```
```
In block/blk-mq.c (ffffffff817c2b02)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
```
```
In lib/rhashtable.c (ffffffff8185ea28)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/percpu_counter.c (ffffffff81920041)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_limited_add
  - lib/percpu_counter.c:__percpu_counter_limited_add
  - lib/percpu_counter.c:percpu_counter_add_batch
```
```
In lib/irq_poll.c (ffffffff81927d9f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_complete
  - lib/irq_poll.c:irq_poll_sched
```
```
In drivers/acpi/osl.c (ffffffff819e3d58)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff819e53b0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff819fd9e1)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff81a08770)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff81a0d758)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff81a0f022)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff81a104c3)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81a12717)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff81a16a7a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81a183e1)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff81a19663)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81a1a666)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff81a1ab6c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81a1c421)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81a1d724)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81a1f236)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81a213cd)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81a22571)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff81a27097)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff81a2918f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81a2b6d6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff81a2c485)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81a2ff1b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81a3474a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff81a35390)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff81a36469)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff81a391bd)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81a3a040)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81a3adcf)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81a3eace)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81a3febc)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81a40c17)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff81a45160)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff81a46816)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81a490ca)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81a4a7ec)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81a4cad5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81a4dd4d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81a4e56d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81a4f909)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81a52186)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81a53127)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81a5442a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81a5548e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81a55f59)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81a5725b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff81a5848f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81a5a37a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a5a953)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81a5cea6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff81a5d2ee)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff81a5f6ea)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81a616d6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/acpi/apei/erst.c (ffffffff81a7a0c9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_write
```
```
In drivers/clk/clk.c (ffffffff81a89249)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_enable_lock
```
```
In drivers/xen/grant-table.c (ffffffff81ab5eae)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/manage.c (ffffffff81ab786a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/time.c (ffffffff81ab7fb5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu_delta
```
```
In drivers/xen/events/events_base.c (ffffffff81ab8c71)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81abe4a9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abec9f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b19ca0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:uart_port_trylock_irqsave
```
```
In drivers/char/random.c (ffffffff81b32b8d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u16
  - drivers/char/random.c:get_random_u8
  - drivers/char/random.c:crng_make_state
```
```
In drivers/char/hpet.c (ffffffff81b38dbd)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/base/syscore.c (ffffffff81b91aae)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/clock_ops.c (ffffffff81bb09b5)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c269d4)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5b140)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
```
In drivers/gpu/drm/drm_flip_work.c (ffffffff81cc8868)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_flip_work.c:drm_can_sleep
  - drivers/gpu/drm/drm_flip_work.c:drm_can_sleep
```
```
In drivers/gpu/drm/drm_fb_helper.c (ffffffff81cd2771)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_check_var
```
```
In drivers/spi/spi.c (ffffffff81cdaac8)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_take_timestamp_post
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6c573)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81dbaf10)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de3083)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de6a96)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45a85)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4f68f)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81e5a6ce)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e62a6c)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
```
```
In drivers/cpuidle/cpuidle.c (ffffffff82224a4a)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8ac2b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e98ca2)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In drivers/hv/hv_common.c (ffffffff81ea19f0)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_common_cpu_init
```
```
In net/core/skbuff.c (ffffffff81ed3417)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/dev.c (ffffffff81efc8f4)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:dev_kfree_skb_any_reason
  - net/core/dev.c:dev_kfree_skb_irq_reason
  - net/core/dev.c:__netif_reschedule
```
```
In net/core/xdp.c (ffffffff81f38c0b)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/core/netpoll.c (ffffffff81f485f6)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/netlink/af_netlink.c (ffffffff81f88e70)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81fe59e9)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff82030962)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff820467d1)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff820603e1)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff82073787)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ioam6.c (ffffffff820d9293)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd975)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eeb23)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In net/handshake/request.c (ffffffff821695d7)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
```
```
In arch/x86/pci/direct.c (ffffffff8396f102)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type1
```
```
In lib/dump_stack.c (ffffffff82177cbc)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack_lvl
  - lib/dump_stack.c:dump_stack_lvl
```
```
In lib/nmi_backtrace.c (ffffffff8219154d)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
```
In lib/objpool.c (ffffffff8219190e)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/objpool.c:objpool_pop
  - lib/objpool.c:objpool_push
```
```
In lib/ratelimit.c (ffffffff82194552)
Location: arch/x86/include/asm/irqflags.h:120
Inline: True
Inline callers:
  - lib/ratelimit.c:___ratelimit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int arch_irqs_disabled_flags(long unsigned int flags);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffff800010084ed4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/arm64/kernel/debug-monitors.c (ffff800010086264)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:kernel_active_single_step
  - arch/arm64/kernel/debug-monitors.c:kernel_disable_single_step
  - arch/arm64/kernel/debug-monitors.c:kernel_enable_single_step
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
```
```
In arch/arm64/kernel/fpsimd.c (ffff80001008871c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
  - arch/arm64/kernel/fpsimd.c:fpsimd_bind_state_to_cpu
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008bc8c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_tls_set
  - arch/arm64/kernel/ptrace.c:compat_tls_set
  - arch/arm64/kernel/ptrace.c:compat_tls_get
  - arch/arm64/kernel/ptrace.c:compat_tls_get
  - arch/arm64/kernel/ptrace.c:compat_vfp_set
  - arch/arm64/kernel/ptrace.c:compat_vfp_set
  - arch/arm64/kernel/ptrace.c:compat_vfp_get
  - arch/arm64/kernel/ptrace.c:compat_vfp_get
  - arch/arm64/kernel/ptrace.c:compat_gpr_set
  - arch/arm64/kernel/ptrace.c:compat_gpr_set
  - arch/arm64/kernel/ptrace.c:compat_gpr_get
  - arch/arm64/kernel/ptrace.c:compat_gpr_get
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_set
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_set
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_get
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_get
  - arch/arm64/kernel/ptrace.c:pac_address_keys_set
  - arch/arm64/kernel/ptrace.c:pac_address_keys_set
  - arch/arm64/kernel/ptrace.c:pac_address_keys_get
  - arch/arm64/kernel/ptrace.c:pac_address_keys_get
  - arch/arm64/kernel/ptrace.c:pac_mask_get
  - arch/arm64/kernel/ptrace.c:pac_mask_get
  - arch/arm64/kernel/ptrace.c:system_call_set
  - arch/arm64/kernel/ptrace.c:system_call_set
  - arch/arm64/kernel/ptrace.c:system_call_get
  - arch/arm64/kernel/ptrace.c:system_call_get
  - arch/arm64/kernel/ptrace.c:tls_set
  - arch/arm64/kernel/ptrace.c:tls_set
  - arch/arm64/kernel/ptrace.c:tls_get
  - arch/arm64/kernel/ptrace.c:tls_get
  - arch/arm64/kernel/ptrace.c:fpr_get
  - arch/arm64/kernel/ptrace.c:fpr_get
  - arch/arm64/kernel/ptrace.c:gpr_set
  - arch/arm64/kernel/ptrace.c:gpr_set
  - arch/arm64/kernel/ptrace.c:gpr_get
  - arch/arm64/kernel/ptrace.c:gpr_get
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/ptrace.c:hw_break_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
```
```
In arch/arm64/kernel/signal.c (ffff800010090fa0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
```
```
In arch/arm64/kernel/traps.c (ffff80001009528c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:unregister_undef_hook
  - arch/arm64/kernel/traps.c:register_undef_hook
  - arch/arm64/kernel/traps.c:die
```
```
In arch/arm64/kernel/insn.c (ffff800010da75e4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
```
```
In arch/arm64/kernel/signal32.c (ffff8000100a1468)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/signal32.c:compat_setup_frame
  - arch/arm64/kernel/signal32.c:compat_setup_frame
  - arch/arm64/kernel/signal32.c:compat_setup_rt_frame
  - arch/arm64/kernel/signal32.c:compat_setup_rt_frame
  - arch/arm64/kernel/signal32.c:compat_setup_rt_frame
  - arch/arm64/kernel/signal32.c:compat_setup_rt_frame
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
```
```
In arch/arm64/kernel/ftrace.c (ffff8000100a19d4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/ftrace.c:ftrace_make_call
```
```
In arch/arm64/kernel/perf_callchain.c (ffff8000100a357c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
```
```
In arch/arm64/kernel/perf_event.c (ffff8000100a4600)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_stop
  - arch/arm64/kernel/perf_event.c:armv8pmu_start
  - arch/arm64/kernel/perf_event.c:armv8pmu_disable_event
  - arch/arm64/kernel/perf_event.c:armv8pmu_enable_event
```
```
In arch/arm64/kernel/kgdb.c (ffff8000100a72b4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/kgdb.c:kgdb_notify
```
```
In arch/arm64/kernel/armv8_deprecated.c (ffff8000100a892c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/armv8_deprecated.c:emulate_swpX
  - arch/arm64/kernel/armv8_deprecated.c:emulate_swpX
  - arch/arm64/kernel/armv8_deprecated.c:emulate_swpX
  - arch/arm64/kernel/armv8_deprecated.c:run_all_insn_set_hw_mode
```
```
In arch/arm64/kernel/crash_dump.c (ffff8000100ab980)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/crash_dump.c:copy_oldmem_page
  - arch/arm64/kernel/crash_dump.c:copy_oldmem_page
```
```
In arch/arm64/kernel/probes/kprobes.c (ffff800010da8590)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/kprobes.c:arch_prepare_kprobe
```
```
In arch/arm64/mm/fault.c (ffff8000100acfd4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:__do_kernel_fault
```
```
In arch/arm64/mm/context.c (ffff8000100afad8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4b98)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In virt/kvm/kvm_main.c (ffff8000100bdae0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_read_guest_cached
  - virt/kvm/kvm_main.c:kvm_read_guest_cached
  - virt/kvm/kvm_main.c:kvm_write_guest_offset_cached
  - virt/kvm/kvm_main.c:kvm_write_guest_offset_cached
  - virt/kvm/kvm_main.c:__kvm_write_guest_page
  - virt/kvm/kvm_main.c:__kvm_write_guest_page
  - virt/kvm/kvm_main.c:__kvm_read_guest_atomic
  - virt/kvm/kvm_main.c:__kvm_read_guest_atomic
  - virt/kvm/kvm_main.c:__kvm_read_guest_page
  - virt/kvm/kvm_main.c:__kvm_read_guest_page
  - virt/kvm/kvm_main.c:kvm_get_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log
  - virt/kvm/kvm_main.c:kvm_get_dirty_log
  - virt/kvm/kvm_main.c:_copy_from_user
  - virt/kvm/kvm_main.c:_copy_from_user
```
```
In virt/kvm/eventfd.c (ffff8000100c0c88)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:irqfd_wakeup
```
```
In virt/kvm/vfio.c (ffff8000100c20e0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/vfio.c:kvm_vfio_set_group
  - virt/kvm/vfio.c:kvm_vfio_set_group
  - virt/kvm/vfio.c:kvm_vfio_set_group
  - virt/kvm/vfio.c:kvm_vfio_set_group
```
```
In virt/kvm/arm/arm.c (ffff8000100c7780)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:_copy_to_user
  - virt/kvm/arm/arm.c:_copy_to_user
  - virt/kvm/arm/arm.c:_copy_from_user
  - virt/kvm/arm/arm.c:_copy_from_user
```
```
In virt/kvm/arm/psci.c (ffff8000100ceda0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/arm/psci.c:kvm_arm_set_fw_reg
  - virt/kvm/arm/psci.c:kvm_arm_set_fw_reg
  - virt/kvm/arm/psci.c:kvm_arm_get_fw_reg
  - virt/kvm/arm/psci.c:kvm_arm_get_fw_reg
  - virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices
  - virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices
  - virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices
  - virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices
  - virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices
  - virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices
```
```
In arch/arm64/kvm/guest.c (ffff8000100d3018)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:copy_core_reg_indices
  - arch/arm64/kvm/guest.c:copy_core_reg_indices
  - arch/arm64/kvm/guest.c:_copy_from_user
  - arch/arm64/kvm/guest.c:_copy_from_user
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d9e1c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:kvm_arm_copy_sys_reg_indices
  - arch/arm64/kvm/sys_regs.c:kvm_arm_copy_sys_reg_indices
  - arch/arm64/kvm/sys_regs.c:kvm_arm_copy_sys_reg_indices
  - arch/arm64/kvm/sys_regs.c:kvm_arm_copy_sys_reg_indices
  - arch/arm64/kvm/sys_regs.c:walk_one_sys_reg
  - arch/arm64/kvm/sys_regs.c:walk_one_sys_reg
  - arch/arm64/kvm/sys_regs.c:kvm_arm_sys_reg_set_reg
  - arch/arm64/kvm/sys_regs.c:kvm_arm_sys_reg_set_reg
  - arch/arm64/kvm/sys_regs.c:kvm_arm_sys_reg_get_reg
  - arch/arm64/kvm/sys_regs.c:kvm_arm_sys_reg_get_reg
  - arch/arm64/kvm/sys_regs.c:reg_to_user
  - arch/arm64/kvm/sys_regs.c:reg_to_user
  - arch/arm64/kvm/sys_regs.c:get_wcr
  - arch/arm64/kvm/sys_regs.c:get_wcr
  - arch/arm64/kvm/sys_regs.c:get_wvr
  - arch/arm64/kvm/sys_regs.c:get_wvr
  - arch/arm64/kvm/sys_regs.c:get_bcr
  - arch/arm64/kvm/sys_regs.c:get_bcr
  - arch/arm64/kvm/sys_regs.c:get_bvr
  - arch/arm64/kvm/sys_regs.c:get_bvr
  - arch/arm64/kvm/sys_regs.c:_copy_from_user
  - arch/arm64/kvm/sys_regs.c:_copy_from_user
```
```
In arch/arm64/kvm/fpsimd.c (ffff8000100dad8c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp
```
```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dd558)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_is_active
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_set_owner
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_unmap_phys_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_reset_mapped_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_phys_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_inject_irq
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
  - virt/kvm/arm/vgic/vgic.c:vgic_flush_pending_lpis
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100dfab0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status
```
```
In virt/kvm/arm/vgic/vgic-mmio.c (ffff8000100e2494)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_write_irq_line_level_info
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_config
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_priority
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cpending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_spending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_read_pending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cenable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_senable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_group
```
```
In virt/kvm/arm/vgic/vgic-mmio-v2.c (ffff8000100e35d8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipends
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipendc
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_target
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgir
```
```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (ffff8000100e4ed8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dispatch_sgi
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_uaccess_write_pending
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_write_irouter
```
```
In virt/kvm/arm/vgic/vgic-kvm-device.c (ffff8000100e623c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_get_attr
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_get_attr
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_set_attr
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_set_attr
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e97fc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
  - virt/kvm/arm/vgic/vgic-its.c:vgic_enable_lpis
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_inject_cached_translation
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_inject_cached_translation
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_trigger_msi
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_resolve_lpi
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_invalidate_cache
  - virt/kvm/arm/vgic/vgic-its.c:vgic_copy_lpi_list
  - virt/kvm/arm/vgic/vgic-its.c:update_lpi_config
```
```
In virt/kvm/arm/vgic/vgic-debug.c (ffff8000100eb698)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-debug.c:vgic_debug_show
```
```
In virt/kvm/arm/arch_timer.c (ffff8000100ee1cc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_get_attr
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_get_attr
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_set_attr
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_set_attr
  - virt/kvm/arm/arch_timer.c:timer_restore_state
  - virt/kvm/arm/arch_timer.c:timer_save_state
```
```
In virt/kvm/arm/pmu.c (ffff8000100ef760)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_get_attr
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_get_attr
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_set_attr
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_set_attr
```
```
In arch/arm64/kvm/hyp/tlb.c (ffff800010daeed4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/tlb.c:__tlb_switch_to_guest_vhe
```
```
In arch/arm/xen/p2m.c (ffff8000100f0568)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
  - arch/arm/xen/p2m.c:__pfn_to_mfn
```
```
In kernel/fork.c (ffff8000100f2090)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:mm_release
  - kernel/fork.c:dup_task_struct
```
```
In kernel/panic.c (ffff8000100f6224)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In kernel/exit.c (ffff8000100fc7c8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/softirq.c (ffff8000100ff5b8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
```
```
In kernel/sysctl.c (ffff800010102cf0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
```
```
In kernel/sysctl_binary.c (ffff800010105588)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
```
```
In kernel/capability.c (ffff8000101063ac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/capability.c:__arm64_sys_capset
  - kernel/capability.c:__arm64_sys_capset
  - kernel/capability.c:__arm64_sys_capset
  - kernel/capability.c:__arm64_sys_capset
  - kernel/capability.c:__arm64_sys_capget
  - kernel/capability.c:__arm64_sys_capget
  - kernel/capability.c:__arm64_sys_capget
  - kernel/capability.c:__arm64_sys_capget
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
```
```
In kernel/ptrace.c (ffff800010109c18)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:generic_ptrace_peekdata
  - kernel/ptrace.c:generic_ptrace_peekdata
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_writedata
  - kernel/ptrace.c:ptrace_writedata
  - kernel/ptrace.c:ptrace_readdata
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/user.c (ffff80001010a300)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/user.c:find_user
```
```
In kernel/signal.c (ffff80001010e5d4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_rt_sigsuspend
  - kernel/signal.c:__arm64_sys_rt_sigsuspend
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:__lock_task_sighand
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:flush_itimer_signals
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffff800010117670)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__arm64_sys_getcpu
  - kernel/sys.c:__arm64_sys_getcpu
  - kernel/sys.c:__arm64_sys_getcpu
  - kernel/sys.c:__arm64_sys_getcpu
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__arm64_sys_setrlimit
  - kernel/sys.c:__arm64_sys_setrlimit
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_compat_sys_getrlimit
  - kernel/sys.c:__arm64_compat_sys_setrlimit
  - kernel/sys.c:__arm64_compat_sys_setrlimit
  - kernel/sys.c:__arm64_sys_setdomainname
  - kernel/sys.c:__arm64_sys_setdomainname
  - kernel/sys.c:__arm64_sys_gethostname
  - kernel/sys.c:__arm64_sys_gethostname
  - kernel/sys.c:__arm64_sys_sethostname
  - kernel/sys.c:__arm64_sys_sethostname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__arm64_compat_sys_times
  - kernel/sys.c:__arm64_compat_sys_times
  - kernel/sys.c:__arm64_sys_times
  - kernel/sys.c:__arm64_sys_times
  - kernel/sys.c:__arm64_sys_getresgid
  - kernel/sys.c:__arm64_sys_getresgid
  - kernel/sys.c:__arm64_sys_getresuid
  - kernel/sys.c:__arm64_sys_getresuid
```
```
In kernel/workqueue.c (ffff800010122228)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/pid.c (ffff80001012441c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/task_work.c (ffff800010125034)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_cancel
```
```
In kernel/params.c (ffff800010126b8c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/kthread.c (ffff800010128bf4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/notifier.c (ffff80001012c1ac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/notifier.c:atomic_notifier_chain_register
```
```
In kernel/async.c (ffff80001012ea7c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/async.c:async_schedule_node_domain
  - kernel/async.c:async_schedule_node_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:lowest_in_progress
```
```
In kernel/ucount.c (ffff800010130050)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/groups.c (ffff800010130fd4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/groups.c:groups_from_user
  - kernel/groups.c:groups_from_user
  - kernel/groups.c:groups_to_user
  - kernel/groups.c:groups_to_user
```
```
In kernel/sched/core.c (ffff80001013de88)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__balance_callback
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:_copy_from_user
  - kernel/sched/core.c:_copy_from_user
Direct callers:
  - kernel/sched/core.c:__schedule_bug
```
```
In kernel/sched/cputime.c (ffff80001013f4a0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffff80001013fd34)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffff80001014d620)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
```
```
In kernel/sched/rt.c (ffff800010151050)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffff8000101578e4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:dl_clear_root_domain
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/wait.c (ffff800010158c8c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:__wake_up_common_lock
  - kernel/sched/wait.c:remove_wait_queue
  - kernel/sched/wait.c:add_wait_queue_exclusive
  - kernel/sched/wait.c:add_wait_queue
```
```
In kernel/sched/swait.c (ffff80001015981c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
  - kernel/sched/swait.c:swake_up_one
```
```
In kernel/sched/completion.c (ffff8000101599d8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
```
```
In kernel/sched/cpudeadline.c (ffff80001015a688)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_clear
```
```
In kernel/sched/topology.c (ffff80001015b21c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/debug.c (ffff800010160e74)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/sched/cpufreq_schedutil.c (ffff8000101653f8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_work
```
```
In kernel/sched/psi.c (ffff800010168128)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In kernel/locking/semaphore.c (ffff800010168964)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:up
  - kernel/locking/semaphore.c:down_timeout
  - kernel/locking/semaphore.c:down_trylock
  - kernel/locking/semaphore.c:down_killable
  - kernel/locking/semaphore.c:down_interruptible
  - kernel/locking/semaphore.c:down
```
```
In kernel/locking/rwsem.c (ffff8000101696e8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
```
```
In kernel/locking/rtmutex.c (ffff800010da6030)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
```
```
In kernel/power/qos.c (ffff80001016d7fc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_write
  - kernel/power/qos.c:pm_qos_power_write
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/power/suspend.c (ffff8000101709f8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_wake
```
```
In kernel/printk/printk.c (ffff800010172fb8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/printk/printk.c:kmsg_dump_register
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_safe.c (ffff800010176964)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/irq/irqdesc.c (ffff800010177dd8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/handle.c (ffff80001017874c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/manage.c (ffff80001017c61c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffff80001017d3d8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/irq/spurious.c:__report_bad_irq
```
```
In kernel/irq/chip.c (ffff80001017feec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
```
```
In kernel/irq/generic-chip.c (ffff8000101815ac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
```
```
In kernel/irq/proc.c (ffff800010185f80)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/pm.c (ffff800010186740)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In kernel/rcu/update.c (ffff800010188c04)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/sync.c (ffff800010189204)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/rcu/sync.c:rcu_sync_func
```
```
In kernel/rcu/srcutree.c (ffff80001018ae90)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffff80001018fafc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:sync_rcu_preempt_exp_done_unlocked
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcutree_offline_cpu
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/rcu/tree.c:rcu_idle_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
```
In kernel/dma/mapping.c (ffff800010193cf8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/dma/coherent.c (ffff8000101959cc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/dma/coherent.c:__dma_release_from_coherent
  - kernel/dma/coherent.c:__dma_alloc_from_coherent
```
```
In kernel/dma/swiotlb.c (ffff800010196c58)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/kcmp.c (ffff8000101979a0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/freezer.c (ffff8000101984a0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/profile.c (ffff80001019946c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/time.c (ffff80001019b3d4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:_copy_from_user
  - kernel/time/time.c:_copy_from_user
```
```
In kernel/time/timer.c (ffff80001019cef0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffff8000101a21e8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:lock_hrtimer_base
```
```
In kernel/time/timekeeping.c (ffff8000101a5690)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
```
```
In kernel/time/timer_list.c (ffff8000101a7bac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_active_timers
```
```
In kernel/time/alarmtimer.c (ffff8000101a9970)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/alarmtimer.c:alarmtimer_get_rtcdev
```
```
In kernel/time/posix-timers.c (ffff8000101accb0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:_copy_from_user
  - kernel/time/posix-timers.c:_copy_from_user
```
```
In kernel/time/itimer.c (ffff8000101b0084)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/itimer.c:__arm64_sys_setitimer
  - kernel/time/itimer.c:__arm64_sys_setitimer
```
```
In kernel/time/clockevents.c (ffff8000101b1358)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_update_freq
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-broadcast.c (ffff8000101b3d70)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_switch_to_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/time/sched_clock.c (ffff8000114491c8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_register
```
```
In kernel/time/tick-oneshot.c (ffff8000101b482c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/tick-oneshot.c:tick_oneshot_mode_active
```
```
In kernel/time/tick-sched.c (ffff8000101b5af8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
```
```
In kernel/futex.c (ffff8000101b730c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/futex.c:__arm64_compat_sys_get_robust_list
  - kernel/futex.c:__arm64_compat_sys_get_robust_list
  - kernel/futex.c:__arm64_compat_sys_get_robust_list
  - kernel/futex.c:__arm64_compat_sys_get_robust_list
  - kernel/futex.c:compat_fetch_robust_entry
  - kernel/futex.c:compat_fetch_robust_entry
  - kernel/futex.c:fetch_robust_entry
  - kernel/futex.c:fetch_robust_entry
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:__arm64_sys_get_robust_list
  - kernel/futex.c:__arm64_sys_get_robust_list
  - kernel/futex.c:__arm64_sys_get_robust_list
  - kernel/futex.c:__arm64_sys_get_robust_list
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/smp.c (ffff8000101bd730)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:generic_exec_single
```
```
In kernel/uid16.c (ffff8000101be1c8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/uid16.c:__arm64_sys_setgroups16
  - kernel/uid16.c:__arm64_sys_setgroups16
  - kernel/uid16.c:__arm64_sys_getgroups16
  - kernel/uid16.c:__arm64_sys_getgroups16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresuid16
  - kernel/uid16.c:__arm64_sys_getresuid16
  - kernel/uid16.c:__arm64_sys_getresuid16
  - kernel/uid16.c:__arm64_sys_getresuid16
  - kernel/uid16.c:__arm64_sys_getresuid16
  - kernel/uid16.c:__arm64_sys_getresuid16
```
```
In kernel/module.c (ffff8000101c1868)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/module.c:flush_module_icache
  - kernel/module.c:flush_module_icache
  - kernel/module.c:copy_chunked_from_user
  - kernel/module.c:copy_chunked_from_user
```
```
In kernel/kexec_core.c (ffff8000101c8bb8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/kexec_core.c:_copy_from_user
  - kernel/kexec_core.c:_copy_from_user
```
```
In kernel/kexec.c (ffff8000101ca578)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
  - kernel/kexec.c:_copy_from_user
  - kernel/kexec.c:_copy_from_user
```
```
In kernel/compat.c (ffff8000101cc468)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/compat.c:get_compat_sigset
  - kernel/compat.c:get_compat_sigset
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:__arm64_compat_sys_sigprocmask
  - kernel/compat.c:__arm64_compat_sys_sigprocmask
  - kernel/compat.c:__arm64_compat_sys_sigprocmask
  - kernel/compat.c:__arm64_compat_sys_sigprocmask
  - kernel/compat.c:put_compat_itimerval
  - kernel/compat.c:put_compat_itimerval
  - kernel/compat.c:get_compat_itimerval
  - kernel/compat.c:get_compat_itimerval
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
```
```
In kernel/cgroup/cgroup.c (ffff8000101d88b0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/rstat.c (ffff8000101d9a18)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/namespace.c (ffff8000101da44c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101db72c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffff8000101ddafc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4704)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
```
```
In kernel/user_namespace.c (ffff8000101e6d80)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_setgroups_write
  - kernel/user_namespace.c:proc_setgroups_write
```
```
In kernel/stop_machine.c (ffff8000101e8ba4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:cpu_stop_should_run
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/audit.c (ffff8000101e9b08)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/kprobes.c (ffff8000101f80bc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_lock
```
```
In kernel/debug/debug_core.c (ffff8000101fa1bc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_flush_swbreak_addr
```
```
In kernel/debug/gdbstub.c (ffff8000101fbaac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:write_mem_msg
```
```
In kernel/debug/kdb/kdb_io.c (ffff8000101fcde8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/seccomp.c (ffff80001020a610)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:_copy_from_user
  - kernel/seccomp.c:_copy_from_user
```
```
In kernel/relay.c (ffff80001020c3c0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
  - kernel/relay.c:relay_file_read
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/delayacct.c (ffff80001020cc38)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffff80001020d9b8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffff80001020e154)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
```
```
In kernel/trace/trace_clock.c (ffff80001020ef9c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffff800010212b14)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/trace/ring_buffer.c (ffff800010218df4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/trace/trace.c (ffff800010221e54)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_generic_entry_update
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
  - kernel/trace/trace.c:_copy_from_user
  - kernel/trace/trace.c:_copy_from_user
```
```
In kernel/trace/trace_functions.c (ffff800010230110)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230a08)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
```
```
In kernel/trace/trace_stack.c (ffff80001023282c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_functions_graph.c (ffff800010232ee4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffff800010236a44)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
```
In kernel/trace/bpf_trace.c (ffff80001024e9ac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:_copy_to_user
  - kernel/trace/bpf_trace.c:_copy_to_user
```
```
In kernel/trace/trace_uprobe.c (ffff800010259650)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:_copy_from_user
  - kernel/trace/trace_uprobe.c:_copy_from_user
```
```
In kernel/irq_work.c (ffff80001025b00c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In kernel/bpf/core.c (ffff80001025f1ac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/syscall.c (ffff800010264fc8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_free_id
```
```
In kernel/bpf/verifier.c (ffff800010269560)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/verifier.c:bpf_verifier_vlog
```
```
In kernel/bpf/helpers.c (ffff8000102769dc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/hashtab.c (ffff80001027908c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
```
```
In kernel/bpf/percpu_freelist.c (ffff80001027c224)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
```
In kernel/bpf/bpf_lru_list.c (ffff80001027cec4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
```
In kernel/bpf/lpm_trie.c (ffff80001027def4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
```
In kernel/bpf/queue_stack_maps.c (ffff80001027f8cc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_push_elem
  - kernel/bpf/queue_stack_maps.c:__stack_map_get
  - kernel/bpf/queue_stack_maps.c:__queue_map_get
```
```
In kernel/bpf/btf.c (ffff800010285dc4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:_copy_from_user
  - kernel/bpf/btf.c:_copy_from_user
```
```
In kernel/bpf/devmap.c (ffff8000102871e0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In kernel/bpf/offload.c (ffff80001028aef4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/bpf/stackmap.c (ffff80001028ba84)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/bpf/cgroup.c (ffff80001028e464)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:_copy_from_user
  - kernel/bpf/cgroup.c:_copy_from_user
```
```
In kernel/events/core.c (ffff800010298e14)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_unpin_context
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:_copy_from_user
  - kernel/events/core.c:_copy_from_user
```
```
In kernel/events/hw_breakpoint.c (ffff8000102a49a8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffff8000102a5a3c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:is_trap_at_addr
```
```
In kernel/rseq.c (ffff8000102ac3e8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - kernel/rseq.c:__arm64_sys_rseq
  - kernel/rseq.c:__arm64_sys_rseq
  - kernel/rseq.c:__arm64_sys_rseq
  - kernel/rseq.c:__arm64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/filemap.c (ffff8000102b2750)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/mempool.c (ffff8000102b57f4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/mempool.c:mempool_free
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_resize
```
```
In mm/maccess.c (ffff8000102b9d38)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffff8000102bc024)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/swap.c (ffff8000102c1800)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffff8000102c3ff0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
```
```
In mm/vmscan.c (ffff8000102ce05c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffff8000102d33f0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
```
```
In mm/util.c (ffff8000102d84d0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/util.c:_copy_from_user
  - mm/util.c:_copy_from_user
```
```
In mm/vmstat.c (ffff8000102da750)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In mm/backing-dev.c (ffff8000102df474)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/percpu.c (ffff8000102e3868)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffff8000102e5710)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
```
```
In mm/compaction.c (ffff8000102ec668)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/workingset.c (ffff8000102f0334)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/gup.c (ffff8000102f1880)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/memory.c (ffff8000102fc238)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffff8000102fd330)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/page_alloc.c (ffff80001031ac1c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/shuffle.c (ffff80001031b2d4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/shuffle.c:arch_local_irq_save
```
```
In mm/dmapool.c (ffff80001032d154)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/hugetlb.c (ffff80001032e620)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/mempolicy.c (ffff800010338140)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_mbind
  - mm/mempolicy.c:__arm64_compat_sys_mbind
  - mm/mempolicy.c:__arm64_compat_sys_set_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_set_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:get_nodes
```
```
In mm/slub.c (ffff8000103496c0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_alloc
  - mm/slub.c:count_partial
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffff800010d9d054)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffff80001035289c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/migrate.c:__arm64_compat_sys_move_pages
  - mm/migrate.c:__arm64_compat_sys_move_pages
  - mm/migrate.c:__arm64_compat_sys_move_pages
  - mm/migrate.c:__arm64_compat_sys_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:store_status
  - mm/migrate.c:store_status
```
```
In mm/huge_memory.c (ffff800010359ad0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035db5c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffff80001036b648)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mod_memcg_obj_state
```
```
In mm/swap_cgroup.c (ffff80001036cc30)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/memory-failure.c (ffff80001037091c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_work_func
  - mm/memory-failure.c:memory_failure_queue
```
```
In mm/page_isolation.c (ffff80001037206c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/balloon_compaction.c (ffff800010377684)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_putback
  - mm/balloon_compaction.c:balloon_page_isolate
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
```
In mm/userfaultfd.c (ffff800010377e68)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In mm/hmm.c (ffff80001037afec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
  - mm/hmm.c:hmm_range_register
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:notifiers_decrement
```
```
In mm/memfd.c (ffff80001037c220)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - mm/memfd.c:__arm64_sys_memfd_create
  - mm/memfd.c:__arm64_sys_memfd_create
```
```
In fs/read_write.c (ffff800010383a54)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_compat_sys_sendfile64
  - fs/read_write.c:__arm64_compat_sys_sendfile64
  - fs/read_write.c:__arm64_compat_sys_sendfile64
  - fs/read_write.c:__arm64_compat_sys_sendfile64
  - fs/read_write.c:__arm64_compat_sys_sendfile
  - fs/read_write.c:__arm64_compat_sys_sendfile
  - fs/read_write.c:__arm64_compat_sys_sendfile
  - fs/read_write.c:__arm64_compat_sys_sendfile
  - fs/read_write.c:__arm64_sys_sendfile64
  - fs/read_write.c:__arm64_sys_sendfile64
  - fs/read_write.c:__arm64_sys_sendfile64
  - fs/read_write.c:__arm64_sys_sendfile64
  - fs/read_write.c:__arm64_sys_sendfile
  - fs/read_write.c:__arm64_sys_sendfile
  - fs/read_write.c:__arm64_sys_sendfile
  - fs/read_write.c:__arm64_sys_sendfile
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:__arm64_sys_llseek
  - fs/read_write.c:__arm64_sys_llseek
```
```
In fs/stat.c (ffff80001038ab28)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In fs/exec.c (ffff80001038bfe0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/exec.c:read_code
```
```
In fs/pipe.c (ffff800010391520)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:pipe_ioctl
  - fs/pipe.c:pipe_ioctl
```
```
In fs/namei.c (ffff80001039ad88)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/namei.c:readlink_copy
  - fs/namei.c:readlink_copy
```
```
In fs/fcntl.c (ffff80001039c7c8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:_copy_from_user
  - fs/fcntl.c:_copy_from_user
```
```
In fs/ioctl.c (ffff80001039e528)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:ioctl_preallocate
  - fs/ioctl.c:ioctl_preallocate
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/ioctl.c:fiemap_fill_next_extent
```
```
In fs/readdir.c (ffff80001039fca4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/readdir.c:__arm64_compat_sys_getdents
  - fs/readdir.c:__arm64_compat_sys_getdents
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:__arm64_sys_getdents
  - fs/readdir.c:__arm64_sys_getdents
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffff8000103a4108)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/select.c:__arm64_compat_sys_pselect6_time32
  - fs/select.c:__arm64_compat_sys_pselect6_time32
  - fs/select.c:__arm64_compat_sys_pselect6_time32
  - fs/select.c:__arm64_compat_sys_pselect6_time32
  - fs/select.c:__arm64_compat_sys_pselect6_time64
  - fs/select.c:__arm64_compat_sys_pselect6_time64
  - fs/select.c:__arm64_compat_sys_pselect6_time64
  - fs/select.c:__arm64_compat_sys_pselect6_time64
  - fs/select.c:__arm64_compat_sys_old_select
  - fs/select.c:__arm64_compat_sys_old_select
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:__arm64_sys_pselect6
  - fs/select.c:__arm64_sys_pselect6
  - fs/select.c:__arm64_sys_pselect6
  - fs/select.c:__arm64_sys_pselect6
  - fs/select.c:__arm64_sys_select
  - fs/select.c:__arm64_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
```
```
In fs/filesystems.c (ffff8000103b34a4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_name
```
```
In fs/namespace.c (ffff8000103b4874)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/namespace.c:exact_copy_from_user
  - fs/namespace.c:exact_copy_from_user
```
```
In fs/seq_file.c (ffff8000103bcdec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffff8000103bef80)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/xattr.c:setxattr
  - fs/xattr.c:setxattr
```
```
In fs/libfs.c (ffff8000103c1ba8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_from_buffer
  - fs/libfs.c:simple_read_from_buffer
  - fs/libfs.c:_copy_from_user
  - fs/libfs.c:_copy_from_user
```
```
In fs/fs-writeback.c (ffff8000103caeb4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
```
```
In fs/splice.c (ffff8000103ce9a0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In fs/utimes.c (ffff8000103d0fe8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__arm64_sys_utime32
  - fs/utimes.c:__arm64_sys_utime32
  - fs/utimes.c:__arm64_sys_utime32
  - fs/utimes.c:__arm64_sys_utime32
```
```
In fs/d_path.c (ffff8000103d1f80)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/d_path.c:__arm64_sys_getcwd
  - fs/d_path.c:__arm64_sys_getcwd
```
```
In fs/statfs.c (ffff8000103d3110)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In fs/nsfs.c (ffff8000103d4958)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
```
```
In fs/fsopen.c (ffff8000103d73fc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_read
  - fs/fsopen.c:fscontext_read
```
```
In fs/buffer.c (ffff8000103d81e4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/direct-io.c (ffff8000103e54c8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ecbf4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ef500)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
```
```
In fs/eventpoll.c (ffff8000103f1d60)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
```
```
In fs/signalfd.c (ffff8000103f3d34)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
```
```
In fs/timerfd.c (ffff8000103f5304)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_poll
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
```
```
In fs/eventfd.c (ffff8000103f6310)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffff8000103f89c4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:_copy_from_user
  - fs/userfaultfd.c:_copy_from_user
```
```
In fs/aio.c (ffff8000103fccb0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:put_reqs_available
  - fs/aio.c:kiocb_set_cancel_fn
  - fs/aio.c:aio_migratepage
```
```
In fs/io_uring.c (ffff800010403fe0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_setup
  - fs/io_uring.c:io_uring_setup
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_cqring_add_event
  - fs/io_uring.c:_copy_from_user
  - fs/io_uring.c:_copy_from_user
```
```
In fs/dax.c (ffff80001040a35c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In fs/crypto/crypto.c (ffff80001040ab78)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In fs/crypto/keyring.c (ffff80001040e2f4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:_copy_from_user
  - fs/crypto/keyring.c:_copy_from_user
```
```
In fs/crypto/policy.c (ffff800010410948)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/crypto/policy.c:_copy_from_user
  - fs/crypto/policy.c:_copy_from_user
```
```
In fs/verity/enable.c (ffff80001041144c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/verity/enable.c:_copy_from_user
  - fs/verity/enable.c:_copy_from_user
```
```
In fs/verity/measure.c (ffff800010412408)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
```
```
In fs/compat_ioctl.c (ffff80001041d600)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
```
```
In fs/binfmt_elf.c (ffff800010420944)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffff8000104219f8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/fhandle.c (ffff80001042997c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
  - fs/fhandle.c:_copy_from_user
  - fs/fhandle.c:_copy_from_user
```
```
In fs/quota/quota.c (ffff8000104358ec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/quota/quota.c:_copy_from_user
  - fs/quota/quota.c:_copy_from_user
```
```
In fs/proc/task_mmu.c (ffff80001043a840)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffff80001043f340)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/proc/base.c:_copy_from_user
  - fs/proc/base.c:_copy_from_user
```
```
In fs/proc/kcore.c (ffff80001044dde0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/proc/kcore.c:_copy_to_user
  - fs/proc/kcore.c:_copy_to_user
```
```
In fs/proc/vmcore.c (ffff80001044eb80)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In fs/proc/page.c (ffff80001044fb50)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/kernfs/dir.c (ffff800010452eb0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_path_from_node
  - fs/kernfs/dir.c:kernfs_name
```
```
In fs/kernfs/file.c (ffff800010455278)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
```
```
In fs/configfs/file.c (ffff800010459618)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_write_file
  - fs/configfs/file.c:configfs_write_file
```
```
In fs/dcookies.c (ffff80001045f550)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/dcookies.c:do_lookup_dcookie
  - fs/dcookies.c:do_lookup_dcookie
```
```
In fs/ext4/ioctl.c (ffff80001048d658)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:_copy_from_user
  - fs/ext4/ioctl.c:_copy_from_user
```
```
In fs/ext4/page-io.c (ffff8000104a36e0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fat/dir.c (ffff8000104e6970)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
```
```
In fs/fat/file.c (ffff8000104eb2a0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fe0b8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/fuse/dev.c (ffff800010501b38)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In fs/pstore/inode.c (ffff80001051a450)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
```
In fs/efivarfs/file.c (ffff80001051bae8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In ipc/compat.c (ffff80001051c74c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - ipc/compat.c:_copy_from_user
  - ipc/compat.c:_copy_from_user
```
```
In ipc/msgutil.c (ffff80001051e2f0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - ipc/msgutil.c:_copy_to_user
  - ipc/msgutil.c:_copy_to_user
  - ipc/msgutil.c:_copy_from_user
  - ipc/msgutil.c:_copy_from_user
```
```
In ipc/msg.c (ffff80001051f198)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/msg.c:compat_ksys_msgsnd
  - ipc/msg.c:compat_ksys_msgsnd
  - ipc/msg.c:ksys_msgsnd
  - ipc/msg.c:ksys_msgsnd
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
```
```
In ipc/sem.c (ffff800010522408)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - ipc/sem.c:_copy_from_user
  - ipc/sem.c:_copy_from_user
```
```
In ipc/shm.c (ffff800010526c2c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - ipc/shm.c:_copy_from_user
  - ipc/shm.c:_copy_from_user
```
```
In ipc/mqueue.c (ffff80001052ad98)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:_copy_from_user
  - ipc/mqueue.c:_copy_from_user
```
```
In security/keys/keyring.c (ffff800010530430)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_read_iterator
```
```
In security/keys/keyctl.c (ffff800010531fc0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/keys/keyctl.c:_copy_to_user
  - security/keys/keyctl.c:_copy_to_user
  - security/keys/keyctl.c:_copy_from_user
  - security/keys/keyctl.c:_copy_from_user
```
```
In security/keys/request_key_auth.c (ffff8000105364bc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/request_key_auth.c:request_key_auth_read
```
```
In security/keys/user_defined.c (ffff800010536ce8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_read
  - security/keys/user_defined.c:user_read
```
```
In security/keys/compat_dh.c (ffff8000105370ec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In security/keys/dh.c (ffff800010538068)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/keys/dh.c:_copy_from_user
  - security/keys/dh.c:_copy_from_user
```
```
In security/keys/keyctl_pkey.c (ffff8000105394c0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
```
In security/keys/big_key.c (ffff80001053a128)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
```
```
In security/keys/trusted.c (ffff80001053b55c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053d388)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:_copy_to_user
  - security/keys/encrypted-keys/encrypted.c:_copy_to_user
```
```
In security/selinux/avc.c (ffff800010546ef8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_ss_reset
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffff80001054fb38)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
```
```
In security/selinux/selinuxfs.c (ffff800010556afc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
```
In security/selinux/ibpkey.c (ffff800010558eb0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/selinux/ss/sidtab.c (ffff80001055b2bc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/smack/smack_lsm.c (ffff800010571174)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
```
```
In security/smack/smackfs.c (ffff800010576388)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/smack/smackfs.c:_copy_from_user
  - security/smack/smackfs.c:_copy_from_user
```
```
In security/tomoyo/common.c (ffff80001057d294)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
```
```
In security/tomoyo/securityfs_if.c (ffff8000105868cc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/apparmor/apparmorfs.c (ffff80001058aea8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:_copy_from_user
  - security/apparmor/apparmorfs.c:_copy_from_user
```
```
In security/apparmor/lsm.c (ffff80001059e698)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
```
In security/apparmor/policy_ns.c (ffff8000105a10c8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In security/apparmor/label.c (ffff8000105a2b48)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:vec_find
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
```
In block/bio.c (ffff8000105dd79c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In block/blk-core.c (ffff8000105e2dc0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-flush.c (ffff8000105e6f14)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffff8000105e8c38)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
  - block/blk-ioc.c:ioc_release_fn
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-exec.c (ffff8000105e9a34)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-softirq.c (ffff8000105ec134)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:trigger_softirq
```
```
In block/blk-mq.c (ffff8000105eff00)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In block/ioctl.c (ffff8000105f85bc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:put_uint
  - block/ioctl.c:put_uint
  - block/ioctl.c:put_int
  - block/ioctl.c:put_int
  - block/ioctl.c:put_ushort
  - block/ioctl.c:put_ushort
  - block/ioctl.c:_copy_from_user
  - block/ioctl.c:_copy_from_user
```
```
In block/genhd.c (ffff8000105fa540)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:disk_block_events
```
```
In block/badblocks.c (ffff8000105fe7b0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_set
```
```
In block/scsi_ioctl.c (ffff800010609470)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:_copy_from_user
  - block/scsi_ioctl.c:_copy_from_user
```
```
In block/bsg.c (ffff80001060a36c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg.c:bsg_scsi_fill_hdr
  - block/bsg.c:bsg_scsi_fill_hdr
```
```
In block/bsg-lib.c (ffff80001060b308)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
```
```
In block/blk-cgroup.c (ffff80001060de6c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_lookup_create
```
```
In block/blk-iocost.c (ffff800010615ad4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
```
In block/mq-deadline.c (ffff800010619930)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:deadline_next_request
```
```
In block/compat_ioctl.c (ffff80001061c780)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_put_uint
  - block/compat_ioctl.c:compat_put_uint
  - block/compat_ioctl.c:compat_put_int
  - block/compat_ioctl.c:compat_put_int
  - block/compat_ioctl.c:compat_put_ushort
  - block/compat_ioctl.c:compat_put_ushort
```
```
In block/blk-zoned.c (ffff80001061fbe8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/blk-zoned.c:_copy_to_user
  - block/blk-zoned.c:_copy_to_user
```
```
In block/blk-mq-debugfs.c (ffff800010623bc8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In block/sed-opal.c (ffff8000106286d0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
```
```
In lib/random32.c (ffff80001062a3ec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/random32.c:__prandom_reseed
```
```
In lib/bitmap.c (ffff80001062b774)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffff8000106329f4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:fault_in_pages_readable
  - lib/iov_iter.c:fault_in_pages_readable
  - lib/iov_iter.c:fault_in_pages_readable
  - lib/iov_iter.c:fault_in_pages_readable
```
```
In lib/kfifo.c (ffff8000106349e0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:_copy_from_user
  - lib/kfifo.c:_copy_from_user
```
```
In lib/percpu-refcount.c (ffff8000106355f0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
```
In lib/once.c (ffff800010637614)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/once.c:__do_once_start
```
```
In lib/refcount.c (ffff8000106379d8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In lib/usercopy.c (ffff800010637eec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/kstrtox.c (ffff800010639b70)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/kstrtox.c:_copy_from_user
  - lib/kstrtox.c:_copy_from_user
```
```
In lib/percpu_counter.c (ffff80001065ef3c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_init
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_add_batch
  - lib/percpu_counter.c:percpu_counter_set
```
```
In lib/checksum.c (ffff800010662360)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/checksum.c:csum_partial_copy_from_user
  - lib/checksum.c:csum_partial_copy_from_user
```
```
In lib/strncpy_from_user.c (ffff800010666b14)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:do_strncpy_from_user
  - lib/strncpy_from_user.c:do_strncpy_from_user
  - lib/strncpy_from_user.c:do_strncpy_from_user
  - lib/strncpy_from_user.c:do_strncpy_from_user
```
```
In lib/strnlen_user.c (ffff800010666dd4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/strnlen_user.c:do_strnlen_user
  - lib/strnlen_user.c:do_strnlen_user
  - lib/strnlen_user.c:do_strnlen_user
  - lib/strnlen_user.c:do_strnlen_user
```
```
In lib/irq_poll.c (ffff800010667e4c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/sbitmap.c (ffff800010669c28)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/irqchip/irq-gic-common.c (ffff80001066cf20)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-common.c:gic_configure_irq
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010673e48)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_send_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_msi_prepare
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800010676e04)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_set_affinity
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_mask
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_unmask
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff800010677524)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_resume
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_suspend
```
```
In drivers/irqchip/irq-mtk-sysirq.c (ffff800010677d30)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_set_type
```
```
In drivers/irqchip/irq-imx-gpcv2.c (ffff8000106787d4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_set_wake
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067ae14)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_unmask_irq
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_mask_irq
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067dba0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_mask
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_unmask
```
```
In drivers/bus/hisi_lpc.c (ffff80001067f880)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_out
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_in
```
```
In drivers/bus/fsl-mc/mc-sys.c (ffff800010681330)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010693e68)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069b22c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set
  - drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069d290)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_set_mux
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a1dec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3eec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_disable
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_enable
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a60fc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_output
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_input
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_unmask
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_mask
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a73fc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_get_pull
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_set_pull
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_enable
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff8000106ac308)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_type
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_wake
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_unmask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_mask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_ack
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106add30)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_wake
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (ffff8000106b13e4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_set_direction
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_disable_free
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_request_enable
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_func_set_mux
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b5694)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_unmask
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_mask
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_set_type
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_set
```
```
In drivers/gpio/gpiolib.c (ffff8000106bff6c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_next
  - drivers/gpio/gpiolib.c:gpiolib_seq_start
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_find
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/gpio/gpiolib.c:_copy_from_user
  - drivers/gpio/gpiolib.c:_copy_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c984c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cd264)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106ce4ac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:davinci_direction_out
  - drivers/gpio/gpio-davinci.c:davinci_direction_in
```
```
In drivers/gpio/gpio-mpc8xxx.c (ffff8000106cf9b0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_mask
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_unmask
  - drivers/gpio/gpio-mpc8xxx.c:ls1028a_gpio_dir_in_init
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d1440)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_free
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_request
```
```
In drivers/gpio/gpio-pl061.c (ffff8000106d3b80)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_input
```
```
In drivers/gpio/gpio-xgene.c (ffff8000106d6948)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in
  - drivers/gpio/gpio-xgene.c:xgene_gpio_set
```
```
In drivers/gpio/gpio-xilinx.c (ffff8000106d7398)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
```
```
In drivers/pci/access.c (ffff8000106db900)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_cfg_access_unlock
  - drivers/pci/access.c:pci_cfg_access_trylock
  - drivers/pci/access.c:pci_bus_set_ops
  - drivers/pci/access.c:pci_bus_write_config_dword
  - drivers/pci/access.c:pci_bus_write_config_word
  - drivers/pci/access.c:pci_bus_write_config_byte
  - drivers/pci/access.c:pci_bus_read_config_dword
  - drivers/pci/access.c:pci_bus_read_config_word
  - drivers/pci/access.c:pci_bus_read_config_byte
```
```
In drivers/pci/pci.c (ffff8000106e5790)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/pci/proc.c (ffff8000106f6744)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/pci/pcie/aer.c (ffff800010704824)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffff800010705d40)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/syscall.c (ffff800010718d94)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071b504)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff8000107244fc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_unmask_leg_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_mask_leg_irq
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072c054)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_unmask_intx_irq
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_mask_intx_irq
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072e954)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800010732a50)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_unmask
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_mask
```
```
In drivers/rapidio/rio.c (ffff80001073c118)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_map_outb_region
  - drivers/rapidio/rio.c:rio_map_inb_region
```
```
In drivers/video/fbdev/core/fbmem.c (ffff800010745178)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/video/fbdev/core/fbcmap.c (ffff800010748e68)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:_copy_to_user
  - drivers/video/fbdev/core/fbcmap.c:_copy_to_user
  - drivers/video/fbdev/core/fbcmap.c:_copy_from_user
  - drivers/video/fbdev/core/fbcmap.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbcon.c (ffff800010753118)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
```
```
In drivers/video/fbdev/imsttfb.c (ffff80001075a094)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:_copy_from_user
  - drivers/video/fbdev/imsttfb.c:_copy_from_user
```
```
In drivers/video/fbdev/mx3fb.c (ffff8000107609c8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_disable_channel
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
```
```
In drivers/acpi/osl.c (ffff800010764364)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_acquire_lock
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffff800010764c1c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/ec.c (ffff800010770a4c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enter_noirq
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stopped
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:ec_transaction_completed
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/acpi/pci_link.c (ffff800010775e40)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/acpica/dsfield.c (ffff80001077d280)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffff80001077df6c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffff80001077e728)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffff80001077f6e0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffff800010781a10)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evregion.c (ffff800010782614)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffff800010782b08)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exconfig.c (ffff800010783a34)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffff800010785444)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffff800010786454)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffff800010787a90)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exstorob.c (ffff800010789fc0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: False
Direct callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffff80001078b4e8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/acpi/acpica/hwpci.c (ffff80001078b8d4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsaccess.c (ffff80001078bad0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsalloc.c (ffff80001078c18c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffff80001078d334)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffff80001078d7dc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffff80001078e27c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffff80001078fd9c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfeval.c (ffff800010790914)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffff800010791250)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffff800010793d10)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffff800010794ae4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffff800010795f00)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffff800010796cd4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffff8000107981e0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffff800010798c44)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffff800010798ee0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffff80001079a4a0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffff80001079bca0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffff80001079c1a8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffff80001079cf04)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffff80001079d2ec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffff80001079da14)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffff80001079e5a0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffff80001079f260)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/acpi/apei/erst.c (ffff8000107adde4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b0654)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
```
In drivers/clk/clk.c (ffff8000107bf9dc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_enable_lock
  - drivers/clk/clk.c:clk_enable_lock
```
```
In drivers/clk/clk-divider.c (ffff8000107c4710)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
```
```
In drivers/clk/clk-gate.c (ffff8000107c571c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffff8000107c5ae0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
```
```
In drivers/clk/clk-mux.c (ffff8000107c62d8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffff8000107c7110)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
```
In drivers/clk/clk-xgene.c (ffff8000107c94e4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/clk-xgene.c:xgene_clk_set_rate
  - drivers/clk/clk-xgene.c:xgene_clk_disable
  - drivers/clk/clk-xgene.c:xgene_clk_enable
  - drivers/clk/clk-xgene.c:xgene_clk_pmd_set_rate
  - drivers/clk/clk-xgene.c:xgene_clk_pmd_recalc_rate
```
```
In drivers/clk/hisilicon/clkgate-separated.c (ffff8000107d01f8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_disable
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_enable
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (ffff8000107d05e8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_set_rate
```
```
In drivers/clk/hisilicon/clk-hisi-phase.c (ffff8000107d0a44)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_set_phase
```
```
In drivers/clk/hisilicon/reset.c (ffff8000107d13ec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/hisilicon/reset.c:hisi_reset_deassert
  - drivers/clk/hisilicon/reset.c:hisi_reset_assert
```
```
In drivers/clk/imx/clk-composite-8m.c (ffff8000107d2484)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_set_rate
```
```
In drivers/clk/imx/clk-divider-gate.c (ffff8000107d2e18)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_disable
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_set_rate
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate
```
```
In drivers/clk/imx/clk-fixup-div.c (ffff8000107d33b4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-div.c:clk_fixup_div_set_rate
```
```
In drivers/clk/imx/clk-fixup-mux.c (ffff8000107d3660)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-mux.c:clk_fixup_mux_set_parent
```
```
In drivers/clk/imx/clk-gate2.c (ffff8000107d3f78)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable_unused
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable
  - drivers/clk/imx/clk-gate2.c:clk_gate2_enable
```
```
In drivers/clk/imx/clk-pfdv2.c (ffff8000107d4950)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_set_rate
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_disable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
```
```
In drivers/clk/imx/clk-lpcg-scu.c (ffff8000107d76c8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_disable
  - drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_enable
```
```
In drivers/clk/mediatek/clk-mux.c (ffff8000107e3648)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_lock
```
```
In drivers/clk/meson/clk-mpll.c (ffff8000107e6cf0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/meson/clk-mpll.c:mpll_set_rate
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (ffff8000107eaa9c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
```
```
In drivers/clk/renesas/rcar-gen3-cpg.c (ffff8000107eb024)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-gen3-cpg.c:cpg_reg_modify
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff8000107ec228)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
```
```
In drivers/clk/rockchip/clk-cpu.c (ffff8000107ee6cc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
```
```
In drivers/clk/rockchip/clk-half-divider.c (ffff8000107eef1c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_set_rate
```
```
In drivers/clk/rockchip/clk-inverter.c (ffff8000107ef350)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase
```
```
In drivers/clk/rockchip/clk-ddr.c (ffff8000107efdbc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_sip_set_rate
```
```
In drivers/clk/rockchip/softrst.c (ffff8000107f0074)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_assert
```
```
In drivers/clk/sunxi/clk-factors.c (ffff8000107f1464)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-factors.c:clk_factors_set_rate
```
```
In drivers/clk/sunxi/clk-a10-ve.c (ffff8000107f2328)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_deassert
  - drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_assert
```
```
In drivers/clk/sunxi/clk-mod0.c (ffff8000107f2690)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-mod0.c:mmc_set_phase
```
```
In drivers/clk/sunxi/clk-sun4i-display.c (ffff8000107f2958)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_deassert
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_assert
```
```
In drivers/clk/sunxi/clk-sun4i-tcon-ch1.c (ffff8000107f2c50)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_rate
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_parent
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_enable
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_disable
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (ffff8000107f3748)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert
```
```
In drivers/clk/sunxi/clk-usb.c (ffff8000107f3b08)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert
```
```
In drivers/clk/sunxi/clk-sun9i-cpus.c (ffff8000107f4200)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_clk_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_mmc_timing.c (ffff8000107f4bb4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mmc_timing.c:sunxi_ccu_set_mmc_timing_mode
```
```
In drivers/clk/sunxi-ng/ccu_reset.c (ffff8000107f4e94)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_deassert
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_assert
```
```
In drivers/clk/sunxi-ng/ccu_div.c (ffff8000107f5218)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_frac.c (ffff8000107f5810)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_set_rate
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_disable
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_enable
```
```
In drivers/clk/sunxi-ng/ccu_gate.c (ffff8000107f5ac8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_mux.c (ffff8000107f6454)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_set_parent
```
```
In drivers/clk/sunxi-ng/ccu_mult.c (ffff8000107f6914)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_phase.c (ffff8000107f6bd0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_phase.c:ccu_phase_set_phase
```
```
In drivers/clk/sunxi-ng/ccu_sdm.c (ffff8000107f708c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
```
```
In drivers/clk/sunxi-ng/ccu_nk.c (ffff8000107f77c8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_nkm.c (ffff8000107f7e9c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_nkmp.c (ffff8000107f8684)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_nm.c (ffff8000107f8df8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_mp.c (ffff8000107f9620)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_rate
```
```
In drivers/clk/versatile/clk-sp810.c (ffff8000107fa03c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_set_parent
```
```
In drivers/dma/virt-dma.c (ffff8000107fe904)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_desc_free
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/dma/amba-pl08x.c (ffff800010800664)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_debugfs_show
  - drivers/dma/amba-pl08x.c:pl08x_resume
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/amba-pl08x.c:pl08x_synchronize
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_cyclic
  - drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_memcpy
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804b8c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_synchronize
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_dma_cyclic
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_slave_sg
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_dma_memcpy
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_issue_pending
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
```
```
In drivers/dma/ipu/ipu_irq.c (ffff80001080ab34)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmap
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_map
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_status
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_ack
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_mask
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmask
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d11c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
  - drivers/dma/ipu/ipu_idmac.c:idmac_pause
  - drivers/dma/ipu/ipu_idmac.c:idmac_issue_pending
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
  - drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
```
```
In drivers/soc/fsl/qbman/bman.c (ffff800010811ce8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_release
  - drivers/soc/fsl/qbman/bman.c:bman_release
  - drivers/soc/fsl/qbman/bman.c:bman_p_irqsource_add
```
```
In drivers/soc/fsl/qbman/qman.c (ffff8000108144a0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_delete_cgr
  - drivers/soc/fsl/qbman/qman.c:qman_enqueue
  - drivers/soc/fsl/qbman/qman.c:set_vdqcr
  - drivers/soc/fsl/qbman/qman.c:qman_p_static_dequeue_add
  - drivers/soc/fsl/qbman/qman.c:qman_p_irqsource_remove
  - drivers/soc/fsl/qbman/qman.c:qman_p_irqsource_add
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081c7d4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
```
```
In drivers/soc/qcom/rpmh.c (ffff80001081cf54)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh.c:rpmh_invalidate
  - drivers/soc/qcom/rpmh.c:rpmh_flush
  - drivers/soc/qcom/rpmh.c:rpmh_write_batch
  - drivers/soc/qcom/rpmh.c:__rpmh_write
  - drivers/soc/qcom/rpmh.c:__rpmh_write
```
```
In drivers/soc/renesas/rcar-sysc.c (ffff80001081e214)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
```
```
In drivers/virtio/virtio.c (ffff8000108211f4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_changed
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826088)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_interrupt
```
```
In drivers/virtio/virtio_pci_common.c (ffff8000108286b4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_vring_interrupt
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b0a8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/xen/grant-table.c (ffff80001082d4b8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_cancel_free_callback
  - drivers/xen/grant-table.c:gnttab_request_free_callback
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/grant-table.c:put_free_entry
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/xen/events/events_base.c (ffff8000108306a0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffff80001083314c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffff800010833ccc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff80001083a890)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
```
```
In drivers/reset/reset-meson.c (ffff80001084d9d4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_level
```
```
In drivers/reset/reset-simple.c (ffff80001084de2c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_update
```
```
In drivers/tty/tty_io.c (ffff800010851e98)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:start_tty
  - drivers/tty/tty_io.c:stop_tty
```
```
In drivers/tty/n_tty.c (ffff800010855c10)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:copy_from_read_buf
```
```
In drivers/tty/tty_ioctl.c (ffff80001085b4d8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
```
```
In drivers/tty/tty_ldisc.c (ffff80001085bf50)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/tty_ldisc.c:tty_unregister_ldisc
  - drivers/tty/tty_ldisc.c:tty_register_ldisc
```
```
In drivers/tty/tty_port.c (ffff80001085e684)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_ldsem.c (ffff80001085f524)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
```
In drivers/tty/tty_jobctrl.c (ffff800010860a30)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
```
```
In drivers/tty/pty.c (ffff800010861e7c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_get_pktmode
  - drivers/tty/pty.c:pty_get_pktmode
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_get_lock
  - drivers/tty/pty.c:pty_get_lock
  - drivers/tty/pty.c:pty_set_lock
  - drivers/tty/pty.c:pty_set_lock
  - drivers/tty/pty.c:pty_write
```
```
In drivers/tty/sysrq.c (ffff800010864b90)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:write_sysrq_trigger
```
```
In drivers/tty/vt/vt_ioctl.c (ffff800010867300)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt_ioctl.c:__vt_event_dequeue
  - drivers/tty/vt/vt_ioctl.c:__vt_event_queue
  - drivers/tty/vt/vt_ioctl.c:_copy_from_user
  - drivers/tty/vt/vt_ioctl.c:_copy_from_user
```
```
In drivers/tty/vt/vc_screen.c (ffff800010867d04)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/tty/vt/selection.c (ffff800010869424)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:_copy_from_user
  - drivers/tty/vt/selection.c:_copy_from_user
```
```
In drivers/tty/vt/keyboard.c (ffff80001086f08c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_clr_kbd_mode_bit
  - drivers/tty/vt/keyboard.c:vt_set_kbd_mode_bit
  - drivers/tty/vt/keyboard.c:vt_reset_keyboard
  - drivers/tty/vt/keyboard.c:vt_reset_unicode
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdskbmeta
  - drivers/tty/vt/keyboard.c:vt_do_kdskbmode
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:kbd_bh
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_get_leds
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/keyboard.c:compute_shiftstate
```
```
In drivers/tty/vt/consolemap.c (ffff8000108701a4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:_copy_from_user
  - drivers/tty/vt/consolemap.c:_copy_from_user
```
```
In drivers/tty/vt/vt.c (ffff8000108792dc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/hvc/hvc_console.c (ffff80001087a228)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_port_destruct
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffff800010882610)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_update_mctrl
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
  - drivers/tty/serial/serial_core.c:_copy_from_user
  - drivers/tty/serial/serial_core.c:_copy_from_user
```
```
In drivers/tty/serial/8250/8250_core.c (ffff800010884ab4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffff80001088b1dc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088c08c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088fd00)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
```
```
In drivers/tty/serial/8250/8250_fsl.c (ffff800010890878)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010891124)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_handle_irq
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff8000108926d8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010896f4c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_break_ctl
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/tty/serial/imx.c (ffff80001089b164)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_timeout
  - drivers/tty/serial/imx.c:imx_uart_break_ctl
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089ebe4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_shutdown
```
```
In drivers/tty/serial/sccnxp.c (ffff8000108a0a80)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_ist
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a2814)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a5e7c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_empty
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a6ebc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_shutdown
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_tx_empty
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffff8000108a7e4c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
```
In drivers/char/mem.c (ffff8000108ab11c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffff8000108ac7e8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:_crng_backtrack_protect
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_fast_load
  - drivers/char/random.c:mix_pool_bytes
```
```
In drivers/char/ttyprintk.c (ffff8000108b1e1c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
```
```
In drivers/char/virtio_console.c (ffff8000108b4c3c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:port_has_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
  - drivers/char/virtio_console.c:find_port_by_vq
  - drivers/char/virtio_console.c:find_port_by_id
  - drivers/char/virtio_console.c:find_port_by_vtermno
```
```
In drivers/char/hw_random/core.c (ffff8000108b7938)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/char/tpm/tpm-dev-common.c (ffff8000108b8cc0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
```
```
In drivers/iommu/iova.c (ffff8000108ce3e8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_cpu_cached_iovas
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:find_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d1894)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_sync_context
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_sync_global
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d626c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_detach_dev
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d9854)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_unmap
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_iova_to_phys
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108db238)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_iova_to_phys
  - drivers/iommu/qcom_iommu.c:qcom_iommu_unmap
  - drivers/iommu/qcom_iommu.c:qcom_iommu_map
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dbd98)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_iotlb_sync
  - drivers/iommu/virtio-iommu.c:viommu_iova_to_phys
  - drivers/iommu/virtio-iommu.c:viommu_unmap
  - drivers/iommu/virtio-iommu.c:viommu_map
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_del_mappings
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
```
```
In drivers/lightnvm/core.c (ffff8000108e002c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:_copy_from_user
  - drivers/lightnvm/core.c:_copy_from_user
```
```
In drivers/base/syscore.c (ffff8000108eb7fc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/devres.c (ffff8000108f0208)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_release_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:devres_release_all
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
  - drivers/base/devres.c:devres_find
  - drivers/base/devres.c:devres_add
```
```
In drivers/base/power/qos.c (ffff8000108fa7a0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/runtime.c (ffff8000108fb20c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
```
In drivers/base/power/wakeirq.c (ffff8000108feb40)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
```
```
In drivers/base/power/wakeup.c (ffff800010903e38)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:pm_save_wakeup_count
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_wakeup_timer_fn
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/power/wakeup.c:wakeup_source_record
```
```
In drivers/base/power/domain.c (ffff800010909e54)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_lock_interruptible_spin
  - drivers/base/power/domain.c:genpd_lock_nested_spin
  - drivers/base/power/domain.c:genpd_lock_spin
```
```
In drivers/base/power/domain_governor.c (ffff80001090ad2c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
```
```
In drivers/base/power/clock_ops.c (ffff80001090b7a4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
```
In drivers/base/regmap/regmap.c (ffff800010913174)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_is_done
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:regmap_lock_spinlock
```
```
In drivers/base/regmap/regmap-debugfs.c (ffff80001091abac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
```
In drivers/block/loop.c (ffff800010924268)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/block/loop.c:loop_get_status_old
  - drivers/block/loop.c:_copy_from_user
  - drivers/block/loop.c:_copy_from_user
```
```
In drivers/block/xen-blkfront.c (ffff8000109297ac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_ioctl
  - drivers/block/xen-blkfront.c:blkif_ioctl
```
```
In drivers/misc/vexpress-syscfg.c (ffff80001092becc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
```
```
In drivers/mfd/htc-i2cpld.c (ffff80001092e354)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffff800010941530)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/ezx-pcap.c:pcap_adc_async
  - drivers/mfd/ezx-pcap.c:pcap_adc_trigger
  - drivers/mfd/ezx-pcap.c:pcap_set_ts_bits
  - drivers/mfd/ezx-pcap.c:ezx_pcap_set_bits
  - drivers/mfd/ezx-pcap.c:ezx_pcap_read
  - drivers/mfd/ezx-pcap.c:ezx_pcap_write
```
```
In drivers/mfd/ab3100-core.c (ffff80001094a520)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
```
```
In drivers/mfd/aat2870-core.c (ffff80001094c740)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/bus.c (ffff800010951940)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:_copy_to_user
  - drivers/nvdimm/bus.c:_copy_to_user
  - drivers/nvdimm/bus.c:_copy_from_user
  - drivers/nvdimm/bus.c:_copy_from_user
```
```
In drivers/dma-buf/dma-buf.c (ffff80001096613c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
```
In drivers/dma-buf/dma-fence.c (ffff80001096754c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
```
```
In drivers/dma-buf/sync_file.c (ffff80001096a6d8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:_copy_to_user
  - drivers/dma-buf/sync_file.c:_copy_to_user
  - drivers/dma-buf/sync_file.c:_copy_from_user
  - drivers/dma-buf/sync_file.c:_copy_from_user
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b8d4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:_copy_from_user
  - drivers/dma-buf/sw_sync.c:_copy_from_user
```
```
In drivers/dma-buf/sync_debug.c (ffff80001096c4b8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_file_debug_remove
  - drivers/dma-buf/sync_debug.c:sync_file_debug_add
  - drivers/dma-buf/sync_debug.c:sync_timeline_debug_remove
  - drivers/dma-buf/sync_debug.c:sync_timeline_debug_add
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096cde4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:_copy_from_user
  - drivers/dma-buf/udmabuf.c:_copy_from_user
```
```
In drivers/scsi/scsi.c (ffff80001096e6b4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
```
```
In drivers/scsi/hosts.c (ffff80001096f740)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
```
```
In drivers/scsi/scsi_ioctl.c (ffff8000109708a0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/scsi_error.c (ffff800010974d44)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
```
```
In drivers/scsi/scsi_lib.c (ffff800010976590)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:sdev_evt_send
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_add_cmd_to_list
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_scan.c (ffff80001097cd80)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097fe88)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/scsi_devinfo.c (ffff800010980c68)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
```
```
In drivers/scsi/scsi_proc.c (ffff800010981518)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:_copy_from_user
  - drivers/scsi/scsi_proc.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffff800010990ef4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffff80001099892c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffff8000109a6a6c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:_copy_to_user
  - drivers/ata/libata-scsi.c:_copy_to_user
```
```
In drivers/ata/libata-eh.c (ffff8000109ac638)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libata-sff.c (ffff8000109b02fc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_interrupt
```
```
In drivers/ata/libata-pmp.c (ffff8000109b3f38)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/ata/libata-acpi.c (ffff8000109b59f0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
```
In drivers/ata/libahci.c (ffff8000109bc530)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_sw_activity_blink
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
```
```
In drivers/gpu/vga/vgaarb.c (ffff8000109c01a8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_release
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/gpu/vga/vgaarb.c:vga_client_register
  - drivers/gpu/vga/vgaarb.c:__vga_set_legacy_decoding
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/spi/spi.c (ffff8000109c4e34)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_bus_lock
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_get_next_queued_message
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_statistics_bytes_tx_show
  - drivers/spi/spi.c:spi_statistics_bytes_rx_show
  - drivers/spi/spi.c:spi_statistics_bytes_show
  - drivers/spi/spi.c:spi_statistics_spi_async_show
  - drivers/spi/spi.c:spi_statistics_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_statistics_spi_sync_show
  - drivers/spi/spi.c:spi_statistics_timedout_show
  - drivers/spi/spi.c:spi_statistics_errors_show
  - drivers/spi/spi.c:spi_statistics_transfers_show
  - drivers/spi/spi.c:spi_statistics_messages_show
```
```
In drivers/spi/spi-fsl-spi.c (ffff8000109cbf10)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/net/tun.c (ffff8000109dc904)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:_copy_to_user
  - drivers/net/tun.c:_copy_to_user
  - drivers/net/tun.c:_copy_from_user
  - drivers/net/tun.c:_copy_from_user
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e6668)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_hwtstamp
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ecbd8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_time_keep
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_get
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_get
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_settime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_gettime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjtime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
```
```
In drivers/net/ethernet/freescale/fman/fman.c (ffff8000109ef608)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fbe88)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a00c50)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (ffff800010a084b4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/cdrom/cdrom.c (ffff800010a0d67c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:_copy_from_user
  - drivers/cdrom/cdrom.c:_copy_from_user
```
```
In drivers/usb/core/hub.c (ffff800010a13bb8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
```
```
In drivers/usb/core/hcd.c (ffff800010a1fcf4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/urb.c (ffff800010a20fac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
  - drivers/usb/core/urb.c:usb_unanchor_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffff800010a22ecc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:sg_complete
```
```
In drivers/usb/core/devio.c (ffff800010a30834)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:async_getcompleted
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:usbdev_vm_open
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
```
```
In drivers/usb/core/devices.c (ffff800010a34a48)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/phy/phy.c (ffff800010a382a8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:usb_remove_phy
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:usb_get_phy
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a47d68)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_reset
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4c984)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4dff8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/pci-quirks.c (ffff800010a502f4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a56efc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a6264c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ohci-hcd.c:fill_async_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6cb24)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_fsbr_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
```
```
In drivers/usb/host/xhci.c (ffff800010a6fbac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a82cf0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
```
In drivers/usb/host/xhci-hub.c (ffff800010a86d1c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8be60)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8c93c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_port_activate
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_chars_in_buffer
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write_room
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_put_char
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8fd48)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/input/serio/serio.c (ffff800010a92ae0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffff800010a98b8c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_get_keycode
  - drivers/input/input.c:input_inject_event
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-compat.c (ffff800010a99364)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/input/input-compat.c:_copy_from_user
  - drivers/input/input-compat.c:_copy_from_user
```
```
In drivers/input/mousedev.c (ffff800010a9c93c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (ffff800010a9ffb8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_handle_set_keycode_v2
  - drivers/input/evdev.c:evdev_handle_set_keycode_v2
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:evdev_handle_get_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/evdev.c:bits_to_user
```
```
In drivers/input/misc/uinput.c (ffff800010aa5144)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:_copy_from_user
  - drivers/input/misc/uinput.c:_copy_from_user
```
```
In drivers/rtc/interface.c (ffff800010aa9738)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
```
```
In drivers/rtc/dev.c (ffff800010aaae74)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:_copy_from_user
  - drivers/rtc/dev.c:_copy_from_user
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aadba8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_getalarm
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setaie
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_set_parent
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab1268)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab4764)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffff800010ab883c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/i2c/i2c-dev.c:_copy_from_user
  - drivers/i2c/i2c-dev.c:_copy_from_user
```
```
In drivers/media/cec/cec-api.c (ffff800010ac2734)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:_copy_from_user
  - drivers/media/cec/cec-api.c:_copy_from_user
```
```
In drivers/pps/pps.c (ffff800010ac5ef8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:_copy_to_user
  - drivers/pps/pps.c:_copy_to_user
  - drivers/pps/pps.c:_copy_from_user
  - drivers/pps/pps.c:_copy_from_user
```
```
In drivers/pps/kapi.c (ffff800010ac6808)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/pps/kapi.c:pps_event
```
```
In drivers/ptp/ptp_clock.c (ffff800010ac757c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffff800010ac8664)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:_copy_to_user
  - drivers/ptp/ptp_chardev.c:_copy_to_user
  - drivers/ptp/ptp_chardev.c:_copy_from_user
  - drivers/ptp/ptp_chardev.c:_copy_from_user
```
```
In drivers/ptp/ptp_sysfs.c (ffff800010ac8fe8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc6f8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010ae07b8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_write
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/watchdog/watchdog_pretimeout.c (ffff800010ae1250)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_notify_pretimeout
```
```
In drivers/md/md.c (ffff800010af35f4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:_copy_from_user
  - drivers/md/md.c:_copy_from_user
```
```
In drivers/md/md-bitmap.c (ffff800010af7d8c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/md/dm.c (ffff800010b01234)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_uevent_add
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:queue_io
```
```
In drivers/md/dm-ioctl.c (ffff800010b09240)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:_copy_from_user
  - drivers/md/dm-ioctl.c:_copy_from_user
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0b798)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:complete_io
  - drivers/md/dm-kcopyd.c:push
```
```
In drivers/md/dm-stats.c (ffff800010b0cd78)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:free_shared_memory
```
```
In drivers/edac/edac_mc.c (0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b13d3c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/edac/ghes_edac.c (ffff800010b15564)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_unregister
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/edac/altera_edac.c (ffff800010b178d4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig
  - drivers/edac/altera_edac.c:altr_edac_device_trig
  - drivers/edac/altera_edac.c:altr_edac_device_trig
  - drivers/edac/altera_edac.c:altr_edac_device_trig
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1fc18)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
```
In drivers/cpuidle/cpuidle.c (ffff800010b270bc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/mmc/core/core.c (ffff800010b2f15c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
  - drivers/mmc/core/core.c:mmc_detach_bus
  - drivers/mmc/core/core.c:mmc_attach_bus
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/block.c (ffff800010b40cac)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_rw_wait_cond
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
```
```
In drivers/mmc/core/queue.c (ffff800010b43d70)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
  - drivers/mmc/core/queue.c:mmc_cqe_recovery_notifier
```
```
In drivers/mmc/host/mmci.c (ffff800010b46264)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_request
  - drivers/mmc/host/mmci.c:mmci_card_busy
```
```
In drivers/leds/led-triggers.c (ffff800010b4a2d8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In drivers/firmware/ti_sci.c (ffff800010b518e4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_release_resource
  - drivers/firmware/ti_sci.c:ti_sci_get_free_resource
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56e40)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_get_init
```
```
In drivers/firmware/efi/arm-runtime.c (ffff800010b61004)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b64be0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_read
  - drivers/clocksource/sh_cmt.c:sh_cmt_stop
  - drivers/clocksource/sh_cmt.c:sh_cmt_start
  - drivers/clocksource/sh_cmt.c:sh_cmt_set_next
  - drivers/clocksource/sh_cmt.c:sh_cmt_start_stop_ch
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65b70)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/of/base.c (ffff800010b6be94)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/of/base.c:of_update_property
  - drivers/of/base.c:of_remove_property
  - drivers/of/base.c:of_add_property
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_match_node
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:of_get_next_available_child
  - drivers/of/base.c:of_get_next_child
  - drivers/of/base.c:of_get_next_parent
  - drivers/of/base.c:of_get_parent
  - drivers/of/base.c:of_device_is_available
  - drivers/of/base.c:of_device_is_compatible
  - drivers/of/base.c:of_find_all_nodes
  - drivers/of/base.c:of_find_property
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_free_phandle_cache
```
```
In drivers/of/dynamic.c (ffff800010b70f04)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_changeset_entry_apply
  - drivers/of/dynamic.c:of_detach_node
  - drivers/of/dynamic.c:of_attach_node
```
```
In drivers/of/resolver.c (ffff800010b76bbc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/of/resolver.c:of_resolve_phandles
```
```
In drivers/mailbox/mailbox.c (ffff800010b7a918)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_request_channel
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/mailbox/pcc.c (ffff800010b7bb3c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_free_channel
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7ee44)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In drivers/remoteproc/remoteproc_debugfs.c (ffff800010b8275c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
```
In drivers/extcon/extcon.c (ffff800010b88600)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - drivers/extcon/extcon.c:extcon_register_notifier
  - drivers/extcon/extcon.c:extcon_set_property
  - drivers/extcon/extcon.c:extcon_get_property
  - drivers/extcon/extcon.c:extcon_set_state
  - drivers/extcon/extcon.c:extcon_get_state
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/memory/fsl_ifc.c (ffff800010b8b248)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/memory/fsl_ifc.c:check_nand_stat
```
```
In drivers/perf/arm-cci.c (ffff800010b91978)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_start
  - drivers/perf/arm-cci.c:cci_pmu_disable
  - drivers/perf/arm-cci.c:cci_pmu_enable
  - drivers/perf/arm-cci.c:pmu_handle_irq
```
```
In drivers/perf/arm-ccn.c (ffff800010b93378)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_timer_handler
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99644)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_start
  - drivers/perf/qcom_l2_pmu.c:get_l2_indirect_reg
  - drivers/perf/qcom_l2_pmu.c:set_l2_indirect_reg
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c8b0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_pmu_isr
```
```
In net/socket.c (ffff800010ba419c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
```
```
In net/core/sock.c (ffff800010baf184)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:groups_to_user
  - net/core/sock.c:groups_to_user
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:_copy_from_user
  - net/core/sock.c:_copy_from_user
```
```
In net/core/skbuff.c (ffff800010bb3e54)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/datagram.c (ffff800010bbcd1c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/core/scm.c (ffff800010bbe52c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
```
```
In net/core/flow_dissector.c (ffff800010bc327c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In net/core/sysctl_net_core.c (ffff800010bc5c94)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffff800010bd41e0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
```
```
In net/core/ethtool.c (ffff800010bdbb40)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_features
  - net/core/ethtool.c:ethtool_get_features
  - net/core/ethtool.c:_copy_from_user
  - net/core/ethtool.c:_copy_from_user
```
```
In net/core/link_watch.c (ffff800010bf3970)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_forget_dev
```
```
In net/core/filter.c (ffff800010c030bc)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
  - net/core/filter.c:sk_get_filter
  - net/core/filter.c:_copy_from_user
  - net/core/filter.c:_copy_from_user
```
```
In net/core/dev_ioctl.c (ffff800010c03f54)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In net/core/netpoll.c (ffff800010c11454)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:refill_skbs
  - net/core/netpoll.c:queue_process
```
```
In net/core/drop_monitor.c (ffff800010c1b940)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/compat.c (ffff800010c32f14)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/sched/sch_generic.c (ffff800010c37cc8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4d7f0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/bpf/test_run.c (ffff800010c52bf0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/bpf/test_run.c:_copy_from_user
  - net/bpf/test_run.c:_copy_from_user
```
```
In net/ipv4/ip_options.c (ffff800010c6179c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get_from_user
  - net/ipv4/ip_options.c:ip_options_get_from_user
```
```
In net/ipv4/ip_sockglue.c (ffff800010c67624)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:_copy_from_user
  - net/ipv4/ip_sockglue.c:_copy_from_user
```
```
In net/ipv4/tcp.c (ffff800010c6ffec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_repair_options_est
  - net/ipv4/tcp.c:tcp_repair_options_est
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_output.c (ffff800010c829f0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8b6d8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
```
```
In net/ipv4/raw.c (ffff800010c972d8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_seticmpfilter
  - net/ipv4/raw.c:raw_seticmpfilter
```
```
In net/ipv4/udp.c (ffff800010c9a798)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:udp_ioctl
```
```
In net/ipv4/arp.c (ffff800010ca3058)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
```
```
In net/ipv4/devinet.c (ffff800010ca6868)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/devinet.c:inet_gifconf
```
```
In net/ipv4/af_inet.c (ffff800010cabda4)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:_copy_from_user
  - net/ipv4/af_inet.c:_copy_from_user
```
```
In net/ipv4/igmp.c (ffff800010cb2890)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
```
```
In net/ipv4/fib_frontend.c (ffff800010cb4098)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (ffff800010cc6464)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
```
In net/ipv4/ipmr.c (ffff800010ccf728)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:_copy_from_user
  - net/ipv4/ipmr.c:_copy_from_user
```
```
In net/xfrm/xfrm_device.c (ffff800010cee26c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffff800010cf00e0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/addrconf.c (ffff800010d00198)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In net/ipv6/route.c (ffff800010d16a80)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:ipv6_route_ioctl
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1c46c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:_copy_from_user
  - net/ipv6/ipv6_sockglue.c:_copy_from_user
```
```
In net/ipv6/raw.c (ffff800010d29298)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (ffff800010d32018)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:_copy_to_user
  - net/ipv6/mcast.c:_copy_to_user
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d36d80)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3ea34)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:_copy_from_user
  - net/ipv6/ip6_flowlabel.c:_copy_from_user
```
```
In net/ipv6/ip6mr.c (ffff800010d47a24)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:_copy_from_user
  - net/ipv6/ip6mr.c:_copy_from_user
```
```
In net/packet/af_packet.c (ffff800010d5b094)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:_copy_from_user
  - net/packet/af_packet.c:_copy_from_user
```
```
In net/wireless/wext-core.c (ffff800010d61210)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/wireless/wext-core.c:_copy_from_user
  - net/wireless/wext-core.c:_copy_from_user
```
```
In net/wireless/wext-priv.c (ffff800010d62740)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:_copy_from_user
  - net/wireless/wext-priv.c:_copy_from_user
```
```
In net/rfkill/core.c (ffff800010d6cf58)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_read
  - net/rfkill/core.c:rfkill_fop_read
  - net/rfkill/core.c:rfkill_blocked
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_init_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_fill_event
```
```
In net/rfkill/input.c (ffff800010d6d9e8)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d76fb0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
```
```
In net/ncsi/ncsi-aen.c (ffff800010d77450)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffff800010d79288)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_alloc_request
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_report_link
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d448)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
```
```
In net/xdp/xsk.c (ffff800010d7fa54)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_destruct_skb
  - net/xdp/xsk.c:_copy_from_user
  - net/xdp/xsk.c:_copy_from_user
```
```
In net/xdp/xdp_umem.c (ffff800010d80cec)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In arch/arm64/lib/uaccess_flushcache.c (ffff800010d83618)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - arch/arm64/lib/uaccess_flushcache.c:__copy_user_flushcache
  - arch/arm64/lib/uaccess_flushcache.c:__copy_user_flushcache
```
```
In lib/dec_and_lock.c (ffff800010d8487c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In lib/dump_stack.c (ffff800010d84b74)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffff800010d8831c)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In lib/idr.c (ffff800010d88cf0)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/klist.c (ffff800010d89c14)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/ratelimit.c (ffff800010d8ed78)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
```
```
In lib/seq_buf.c (ffff800010d90058)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_to_user
  - lib/seq_buf.c:seq_buf_to_user
```
```
In lib/xarray.c (ffff800010d9ac60)
Location: arch/arm64/include/asm/irqflags.h:82
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
```
**Symbols:**

```
ffff800010084660-ffff80001008466c: arch_irqs_disabled_flags (STB_LOCAL)
ffff800010131418-ffff800010131424: arch_irqs_disabled_flags (STB_LOCAL)
ffff800010787a90-ffff800010787a9c: arch_irqs_disabled_flags (STB_LOCAL)
ffff800010789fc0-ffff800010789fcc: arch_irqs_disabled_flags (STB_LOCAL)
ffff800010791250-ffff80001079125c: arch_irqs_disabled_flags (STB_LOCAL)
ffff80001079a4a0-ffff80001079a4ac: arch_irqs_disabled_flags (STB_LOCAL)
ffff80001079d2ec-ffff80001079d2f8: arch_irqs_disabled_flags (STB_LOCAL)
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
In init/main.c (c03036d4)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/arm/mm/l2c-common.c (c0323030)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - arch/arm/mm/l2c-common.c:outer_disable
```
```
In arch/arm/mm/cache-l2x0.c (c032429c)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
```
```
In arch/arm/common/mcpm_entry.c (c0325c1c)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
```
```
In kernel/params.c (c037953c)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (c0e99e74)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
```
```
In kernel/sched/idle.c (c038fc84)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/rt.c (c039c30c)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (c039fe64)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/power/suspend.c (c03bb360)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/handle.c (c03c9ee4)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (c03dc438)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
```
```
In kernel/dma/mapping.c (c03e1064)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/time/sched_clock.c (c15232a0)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_register
```
```
In kernel/smp.c (c04053ec)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/trace/ftrace.c (c0451a4c)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (c045bc78)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (c046ea8c)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/irq_work.c (c048e0ac)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
```
```
In kernel/bpf/stackmap.c (c04bb124)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/hw_breakpoint.c (c04d3f4c)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/slub.c (c054f824)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/buffer.c (c05b3314)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
```
```
In block/blk-core.c (c078f12c)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-exec.c (c0795e74)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/base/syscore.c (c09d9808)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/misc/vexpress-syscfg.c (c0a0a574)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
```
```
In drivers/scsi/scsi_lib.c (c0a4af30)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/i2c/i2c-core-base.c (c0b92210)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c0b956b0)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c0bf8c44)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (c0c01c48)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/firmware/tegra/bpmp.c (c0c41938)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
```
```
In net/core/skbuff.c (c0cd214c)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (c0ce46d4)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (c0d292f8)
Location: arch/arm/include/asm/irqflags.h:179
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In init/main.c (c0000000000101a0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/powerpc/kernel/irq.c (c00000000001b7dc)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/kernel/irq.c:force_external_irq_replay
  - arch/powerpc/kernel/irq.c:prep_irq_for_idle_irqsoff
  - arch/powerpc/kernel/irq.c:restore_interrupts
```
```
In arch/powerpc/kernel/process.c (c0000000000217ac)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:__switch_to
  - arch/powerpc/kernel/process.c:__switch_to
```
```
In arch/powerpc/kernel/idle.c (c0000000000234d8)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/kernel/idle.c:arch_cpu_idle
```
```
In arch/powerpc/kernel/time.c (c00000000002bbf4)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:arch_irq_work_raise
  - arch/powerpc/kernel/time.c:arch_irq_work_raise
```
```
In arch/powerpc/kernel/traps.c (c00000000002dac0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:_exception
  - arch/powerpc/kernel/traps.c:_exception_pkey
```
```
In arch/powerpc/kernel/setup-common.c (c00000000002fca8)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:ppc_panic_event
```
```
In arch/powerpc/kernel/setup_64.c (c00000000003118c)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup_64.c:panic_smp_self_stop
```
```
In arch/powerpc/kernel/watchdog.c (c0000000000374c4)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:stop_watchdog
  - arch/powerpc/kernel/watchdog.c:stop_watchdog
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
```
```
In arch/powerpc/kernel/rtas.c (c00000000003f548)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:rtas_give_timebase
```
```
In arch/powerpc/kernel/rtasd.c (c00000000004074c)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In arch/powerpc/kernel/smp.c (c00000000005433c)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:nmi_ipi_lock_start
  - arch/powerpc/kernel/smp.c:nmi_ipi_lock_start
```
```
In arch/powerpc/kernel/crash.c (c000000000070dbc)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/kernel/crash.c:default_machine_crash_shutdown
  - arch/powerpc/kernel/crash.c:crash_ipi_callback
```
```
In arch/powerpc/kernel/machine_kexec_64.c (c000000000071754)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec
  - arch/powerpc/kernel/machine_kexec_64.c:kexec_smp_down
```
```
In arch/powerpc/mm/book3s64/slb.c (c00000000008f50c)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/slb.c:switch_slb
  - arch/powerpc/mm/book3s64/slb.c:preload_new_slb_context
  - arch/powerpc/mm/book3s64/slb.c:preload_new_slb_context
  - arch/powerpc/mm/book3s64/slb.c:slb_setup_new_exec
  - arch/powerpc/mm/book3s64/slb.c:slb_setup_new_exec
  - arch/powerpc/mm/book3s64/slb.c:slb_flush_and_restore_bolted
  - arch/powerpc/mm/book3s64/slb.c:slb_flush_and_restore_bolted
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bdfb8)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In arch/powerpc/platforms/powernv/setup.c (c0000000000c1d98)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-call.c (c0000000000c2248)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-call.c:opal_call
```
```
In arch/powerpc/platforms/powernv/opal-nvram.c (c0000000000c8db0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_write
  - arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_write
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c0000000000cd204)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_shutdown
```
```
In arch/powerpc/platforms/powernv/smp.c (c0000000000cdedc)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_cpu_kill_self
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_cpu_kill_self
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9e50)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_mach_cpu_die
```
```
In arch/powerpc/xmon/xmon.c (c000000000110950)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:xmon_core
```
```
In arch/powerpc/perf/core-book3s.c (c000000000128684)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:power_pmu_enable
```
```
In kernel/params.c (c000000000171084)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (c000000000ee2fe4)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/idle.c (0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In kernel/sched/rt.c (c0000000001a1f48)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (c0000000001a6978)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/power/suspend.c (c0000000001c8ad8)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/handle.c (c0000000001d25f8)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (c0000000001e991c)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
```
```
In kernel/dma/mapping.c (c0000000001f3fd4)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/smp.c (c0000000002235a4)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/stop_machine.c (c0000000002590a0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/ftrace.c (c000000000292dec)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (c0000000002a0bf0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (c0000000002bdbd0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/irq_work.c (c0000000002febfc)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In kernel/bpf/stackmap.c (c000000000337a3c)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/hw_breakpoint.c (c00000000035729c)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/slub.c (0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In fs/buffer.c (0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In block/blk-core.c (0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In block/blk-exec.c (c00000000077e7d4)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/tty/hvc/hvsi_lib.c (c00000000091cc20)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In drivers/base/syscore.c (c000000000982f04)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/scsi/scsi_lib.c (c000000000a30dc0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/i2c/i2c-core-base.c (c000000000b940b4)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c000000000b98608)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (c000000000c1df04)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/skbuff.c (c000000000c8bfc8)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (c000000000ca4e58)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (c000000000cfe114)
Location: arch/powerpc/include/asm/hw_irq.h:169
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In init/main.c (ffffffe0000b4386)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/params.c (ffffffe0000de4ba)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (ffffffe0008c5460)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
```
```
In kernel/sched/idle.c (ffffffe0000ee004)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/rt.c (ffffffe0000f9214)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffe0000fb882)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/irq/handle.c (ffffffe00011316a)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (ffffffe00012322e)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
```
```
In kernel/dma/mapping.c (ffffffe000126086)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/time/sched_clock.c (ffffffe00000a672)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_register
```
```
In kernel/smp.c (ffffffe0001408a8)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/trace/ftrace.c (ffffffe000173104)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (ffffffe00017a914)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (ffffffe00018a3ec)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/irq_work.c (ffffffe00019a054)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffe0001bf5f8)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/slub.c (ffffffe00023ce28)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/buffer.c (ffffffe000292b50)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
```
```
In block/blk-core.c (ffffffe000424092)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-exec.c (ffffffe000429f4a)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dec74)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b8e0c)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bbb02)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
```
```
In net/core/skbuff.c (ffffffe00074513a)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (ffffffe000755006)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (ffffffe00078d62a)
Location: arch/riscv/include/asm/irqflags.h:38
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In init/main.c (ffffffff810028e8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810203eb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/irq.c (ffffffff810287fb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106d716)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/kvm.c (ffffffff81076b32)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8108283d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In kernel/params.c (ffffffff810c1c81)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (ffffffff81a6eec8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/idle.c (ffffffff810da1f0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810e32f0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810e9533)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810eb3c9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/irq/handle.c (ffffffff8110ec31)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (ffffffff81120846)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
```
```
In kernel/dma/mapping.c (ffffffff81126f12)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/smp.c (ffffffff81147363)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/trace/ftrace.c (ffffffff811926ed)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (ffffffff8119b1a7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ad609)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/irq_work.c (ffffffff811d2ea2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811fb915)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/hw_breakpoint.c (ffffffff81211e7e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/slub.c (ffffffff812a2388)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/buffer.c (ffffffff81319b0d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In block/blk-core.c (ffffffff814dd04e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-exec.c (ffffffff814e35c3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/acpi/osl.c (ffffffff815ca319)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815ca8cb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/pci_link.c (ffffffff815d9c38)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff815df63b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff815e111d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815e1c85)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff815e232d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815e3230)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815e5266)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815e5a6c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815e5ec2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815e67ff)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff815e6ad1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815e75e8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815e7cca)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815e8826)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e970e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815e9daf)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815eb489)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815ec311)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815ed917)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815efbe0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815f1961)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815f1d86)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff815f1f99)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff815f25e1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815f34b5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815f3836)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815f4094)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815f5c68)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815f60e9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f6c50)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815f9190)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815f9d3e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815fafc8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815fba70)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff815fcd59)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815fd578)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff815fd7b1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815fde12)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff815fefe0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff815ff3a9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815fff23)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8160046b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816007bd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816010e1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff81601aa2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/xen/manage.c (ffffffff8162b268)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8162c236)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff8162ee22)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f4f3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
```
In drivers/base/syscore.c (ffffffff816c5d28)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/scsi/scsi_lib.c (ffffffff817276b2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81865939)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81872b1e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/skbuff.c (ffffffff818bad0d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (ffffffff818d041e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (ffffffff8190ada6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In init/main.c (ffffffff81000dd3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105db41)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/kvm.c (ffffffff81066432)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff810715b8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In kernel/params.c (ffffffff810b0469)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (ffffffff81a2b296)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/idle.c (ffffffff810c91e2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810d23fb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810d8ffe)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810db3e4)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/power/suspend.c (ffffffff810f2640)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/handle.c (ffffffff810ff97c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (ffffffff81113c2a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
```
```
In kernel/dma/mapping.c (ffffffff8111996a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/smp.c (ffffffff8113a63e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/trace/ftrace.c (ffffffff811857f8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (ffffffff8118e227)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a0494)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/irq_work.c (ffffffff811c5c62)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811ee660)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/hw_breakpoint.c (ffffffff81204c09)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/slub.c (ffffffff81293e63)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/buffer.c (ffffffff8130a6b7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In block/blk-core.c (ffffffff814cd9f9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-exec.c (ffffffff814d3f3e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/acpi/osl.c (ffffffff815b3394)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815b3bc9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/pci_link.c (ffffffff815c3853)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff815cae1b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff815cc798)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815cd2fb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff815cd99e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815ce89c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815d08cd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815d10ce)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815d151f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815d1e57)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff815d2124)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815d2c36)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815d3305)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815d3e4b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815d4d31)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815d53cd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815d6aa2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815d7925)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815d8f0f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815db1bc)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815dcf03)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815dd31e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff815dd52c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff815ddb6f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815dea3e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815dedba)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815df613)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815e0d8f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815e163e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815e23bf)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815e46ca)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815e5273)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815e64f8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815e6f9b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff815e827f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815e8a99)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff815e8ccd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815e952e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff815ea4d2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff815ea896)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815eb40b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815eb935)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff815ebc7d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff815ec59c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff815ecf58)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/nfit/core.c (ffffffff815f53ad)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_label_write
```
```
In drivers/base/syscore.c (ffffffff816a0fa3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/scsi/scsi_lib.c (ffffffff81700add)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182e5d7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8183c8f9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/skbuff.c (ffffffff81874c58)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (ffffffff81886299)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (ffffffff818c4b41)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In init/main.c (ffffffff810028e8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102024b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/irq.c (ffffffff8102865b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106dbc6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/kvm.c (ffffffff81076ae2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff810827ed)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In kernel/params.c (ffffffff810c11d1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (ffffffff81adb2d8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/idle.c (ffffffff810d653d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810df670)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810e6173)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810e84f9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/power/suspend.c (ffffffff810ff52f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/handle.c (ffffffff8110cb21)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/rcu/tree.c (ffffffff8111e736)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
```
```
In kernel/dma/mapping.c (ffffffff81124e02)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/smp.c (ffffffff81145213)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/trace/ftrace.c (ffffffff811904bd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (ffffffff81198f77)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ab3d9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/irq_work.c (ffffffff811d0c72)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811f96e5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120fc1e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/slub.c (ffffffff812a0198)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/buffer.c (ffffffff813175dd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In block/blk-core.c (ffffffff814d90de)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-exec.c (ffffffff814df653)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/acpi/osl.c (ffffffff815cae68)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815cb5fb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/pci_link.c (ffffffff815dcdc8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff815e4c8b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff815e748f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815e898c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff815e9868)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815eaff8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815eef46)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815efce5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815f02d8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815f1259)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff815f169d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815f2943)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815f34da)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815f494b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815f64fd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815f6e47)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815fa940)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815fc38c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815fe0b5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81601e4f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81604f36)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff816056ee)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff81605a69)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff81606575)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816087e4)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81608d83)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81609c9a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8160c769)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8160cf3b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8160ddce)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff816116a0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff8161283d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81614653)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81615779)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81616f5a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81617ca2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff816180bc)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81618804)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8161aa7b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff8161b091)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8161c250)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8161ce00)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8161d523)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8161e26d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff8161ee89)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81620459)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81620863)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81621a5f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff816226ec)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff81624021)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81625280)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/xen/manage.c (ffffffff81659508)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8165a346)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff8165cdf2)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d4c3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
```
In drivers/base/syscore.c (ffffffff816f41f8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/scsi/scsi_lib.c (ffffffff81766482)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81861b36)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81864b7a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b66c9)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818c450e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/skbuff.c (ffffffff8190bd0d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (ffffffff8192141e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (ffffffff8195bdd6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In init/main.c (ffffffff810028e8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102049b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a726e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
```
In arch/x86/xen/irq.c (ffffffff810292eb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/xen/multicalls.c (ffffffff810298e5)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/kernel/traps.c (ffffffff81032f15)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
```
In arch/x86/kernel/ioport.c (ffffffff810363af)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103ec5b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e99e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:x2apic_get_apic_id
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106fe46)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/kvm.c (ffffffff81078c42)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079f48)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/fault.c (ffffffff8108197c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108490d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In arch/x86/mm/tlb.c (ffffffff81089a8a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c6272)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/params.c (ffffffff810c9601)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (ffffffff81ae77bd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/idle.c (ffffffff810e1e3d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810eb229)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810efe45)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810f27fb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/power/suspend.c (ffffffff8110a83f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/irq/handle.c (ffffffff81118051)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/manage.c (ffffffff8111b463)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
```
```
In kernel/rcu/tree.c (ffffffff8112a5e1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__rcu_read_unlock
  - kernel/rcu/tree.c:__call_rcu
```
```
In kernel/dma/mapping.c (ffffffff81131442)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/smp.c (ffffffff81151df3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/trace/ftrace.c (ffffffff8119e04d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (ffffffff811a6bf7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b9249)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/irq_work.c (ffffffff811def32)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81208185)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/hw_breakpoint.c (ffffffff8121eb2e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/slub.c (ffffffff812b02d8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/buffer.c (ffffffff813291cd)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In block/blk-core.c (ffffffff814f1cf1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-exec.c (ffffffff814f84c3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In lib/scatterlist.c (ffffffff815309c8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/acpi/osl.c (ffffffff815e4d08)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815e549b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/pci_link.c (ffffffff815f6c88)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/x86/apple.c (ffffffff815feb3b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff8160133f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff8160283c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff81603718)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81604ea8)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff81608df6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81609b95)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8160a188)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8160b109)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff8160b54d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8160c7f3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff8160d38a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8160e7fb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816103ad)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81610cf7)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff816147f0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8161623c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81617f65)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8161bcff)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8161ede6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8161f59e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff8161f919)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsalloc.c (ffffffff81620425)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff81622694)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81622c33)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81623b4a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81626619)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81626deb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81627c7e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psutils.c (ffffffff8162b550)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff8162c6ed)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff8162e503)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff8162f629)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81630e0a)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81631b52)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81631f6c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816326b4)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8163492b)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81634f41)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81636100)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81636cb0)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816373d3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8163811d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
```
In drivers/acpi/acpica/utxface.c (ffffffff81638d39)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff8163a309)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8163a713)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8163b90f)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8163c59c)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_os_allocate
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8163ded1)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8163f130)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
```
In drivers/xen/manage.c (ffffffff81673b08)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/time.c (ffffffff816741cb)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu_delta
```
```
In drivers/xen/events/events_base.c (ffffffff8167491d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81677402)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677ad3)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
```
In drivers/base/syscore.c (ffffffff8170ea28)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/scsi/scsi_lib.c (ffffffff81781b32)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187cd46)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8187fdda)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d2979)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e088e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/skbuff.c (ffffffff8192ce2d)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (ffffffff8194328e)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (ffffffff8197e1b6)
Location: arch/x86/include/asm/irqflags.h:162
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
