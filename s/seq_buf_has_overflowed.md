# Function: <code>seq_buf_has_overflowed</code>

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
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/power-traces.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In lib/swiotlb.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/iommu/iommu-traces.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/dma-buf/fence.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In net/core/net-traces.c (0)
Location: include/linux/seq_buf.h:44
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
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/power-traces.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In lib/swiotlb.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/iommu/iommu-traces.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/dma-buf/fence.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In net/core/net-traces.c (0)
Location: include/linux/seq_buf.h:44
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
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/cgroup.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/power-traces.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In lib/swiotlb.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/iommu/iommu-traces.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In net/core/net-traces.c (0)
Location: include/linux/seq_buf.h:44
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
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:44
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:44
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
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:45
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
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:45
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
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:45
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
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:45
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
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:45
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
In kernel/trace/ring_buffer.c (ffffffff811b91d2)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811c2f6b)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_bin_fmt
  - kernel/trace/trace.c:print_hex_fmt
  - kernel/trace/trace.c:print_hex_fmt
  - kernel/trace/trace.c:print_raw_fmt
  - kernel/trace/trace.c:print_raw_fmt
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_output.c (ffffffff811c65db)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_seq.c (ffffffff811c7a5e)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ceb06)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d7539)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff811de602)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811f22b9)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
```
```
In mm/memcontrol.c (ffffffff812f538a)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
```
```
In lib/seq_buf.c (ffffffff815f00b7)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_putmem_hex
  - lib/seq_buf.c:seq_buf_bprintf
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
In kernel/trace/ring_buffer.c (ffffffff811b6be2)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811c0b7b)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_bin_fmt
  - kernel/trace/trace.c:print_hex_fmt
  - kernel/trace/trace.c:print_hex_fmt
  - kernel/trace/trace.c:print_raw_fmt
  - kernel/trace/trace.c:print_raw_fmt
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_output.c (ffffffff811c3c78)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_seq.c (ffffffff811c515e)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cbfe6)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d4609)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff811dcd64)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:save_cmdstr
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811f0c89)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
```
```
In mm/memcontrol.c (ffffffff813009ea)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
```
```
In lib/seq_buf.c (ffffffff81614817)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_putmem_hex
  - lib/seq_buf.c:seq_buf_bprintf
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
In kernel/trace/ring_buffer.c (ffffffff811b75e2)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811c1b08)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/trace/trace_output.c (ffffffff811c4d88)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_seq.c (ffffffff811c639f)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cd316)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d5c99)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff811de575)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811f1be9)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
```
```
In mm/memcontrol.c (ffffffff81307827)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
```
```
In lib/seq_buf.c (ffffffff815f7ea3)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_putmem_hex
  - lib/seq_buf.c:seq_buf_bprintf
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
In kernel/trace/ring_buffer.c (ffffffff811e17e2)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811ec6a8)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/trace/trace_output.c (ffffffff811f02c8)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_seq.c (ffffffff811f198f)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f9ad5)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff81202a49)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff8120ddf5)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff81222d89)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
```
```
In mm/memcontrol.c (ffffffff81353e14)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
```
```
In lib/seq_buf.c (ffffffff81665675)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_putmem_hex
  - lib/seq_buf.c:seq_buf_bprintf
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
In kernel/trace/ring_buffer.c (ffffffff81218412)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff81224891)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/trace/trace_output.c (ffffffff812288f3)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_seq.c (ffffffff8122a2d1)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81233ab9)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff8123df02)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff8124a1c3)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff81262cd9)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
```
```
In mm/memcontrol.c (ffffffff813cbe62)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
```
```
In lib/seq_buf.c (ffffffff8177fc7f)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_putmem_hex
  - lib/seq_buf.c:seq_buf_bprintf
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
In kernel/trace/ring_buffer.c (ffffffff8126196f)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff8126fa01)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/trace/trace_output.c (ffffffff81273fb3)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_seq.c (ffffffff81275ad1)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812802c9)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff8128b8a2)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff81298dea)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff812b4669)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
```
```
In mm/memcontrol.c (ffffffff81450b5b)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (ffffffff8203ca41)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_putmem_hex
  - lib/seq_buf.c:seq_buf_bprintf
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
In kernel/trace/ring_buffer.c (ffffffff812789ef)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff81286c50)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/trace/trace_output.c (ffffffff8128b8dc)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_seq.c (ffffffff8128d491)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129ce69)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff812a87a2)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b5fb6)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff812d6fd9)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_char
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
```
```
In mm/memcontrol.c (ffffffff814865d2)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (ffffffff820bb04e)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_putmem_hex
  - lib/seq_buf.c:seq_buf_bprintf
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
In kernel/trace/ring_buffer.c (ffffffff812934aa)
Location: include/linux/seq_buf.h:53
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff812a1d20)
Location: include/linux/seq_buf.h:53
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/trace/trace_output.c (ffffffff812a6cac)
Location: include/linux/seq_buf.h:53
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_seq.c (ffffffff812a8881)
Location: include/linux/seq_buf.h:53
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b8549)
Location: include/linux/seq_buf.h:53
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff812c44b2)
Location: include/linux/seq_buf.h:53
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d263f)
Location: include/linux/seq_buf.h:53
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff812f4ae9)
Location: include/linux/seq_buf.h:53
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_char
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
```
```
In mm/memcontrol.c (ffffffff814b608a)
Location: include/linux/seq_buf.h:53
Inline: True
```
```
In lib/seq_buf.c (ffffffff8219595e)
Location: include/linux/seq_buf.h:53
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_putmem_hex
  - lib/seq_buf.c:seq_buf_bprintf
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
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:45
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
In kernel/trace/ring_buffer.c (c045ae94)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (c0465278)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (c0468e34)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_seq.c (c046a568)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
```
```
In kernel/trace/trace_functions_graph.c (c046ff0c)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (c0478878)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_probe.c (c0488ec4)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
```
```
In mm/memcontrol.c (c0554484)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
```
```
In lib/seq_buf.c (c0e8a6d0)
Location: include/linux/seq_buf.h:45
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_putmem_hex
  - lib/seq_buf.c:seq_buf_bprintf
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
In arch/powerpc/kernel/process.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:45
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
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:45
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
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:45
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
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:45
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
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:45
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
In kernel/trace/ring_buffer.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/seq_buf.h:45
Inline: True
```
</details>
</li>
</ul>

## Differences
