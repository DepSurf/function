# Function: <code>perf_arch_fetch_caller_regs</code>

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
In <code>ppc64el</code>: Absent ⚠️
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
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In arch/riscv/kernel/ptrace.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/trace/power-traces.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/trace/rpm-traces.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In net/core/net-traces.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/perf_event.h:1083
Inline: True
```
</details>
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
