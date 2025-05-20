# Function: <code>__lse__cmpxchg_case_mb_16</code>

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
In virt/kvm/kvm_main.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In virt/kvm/arm/arm.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/fork.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/panic.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/exit.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/task_work.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/cred.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/smpboot.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/ucount.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/kmod.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/module.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/acct.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/irq_work.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In kernel/jump_label.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/filemap.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/oom_kill.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/page-writeback.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/swap.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/vmscan.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/mmzone.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/backing-dev.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/gup.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/mmap.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/frontswap.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/slub.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/memory-failure.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/cleancache.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/page_idle.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/hmm.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In mm/memfd.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/open.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/super.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/exec.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/namei.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/dcache.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/inode.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/file.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/nsfs.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/buffer.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/direct-io.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/notify/mark.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/eventpoll.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/aio.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/io_uring.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/crypto/keysetup.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/verity/enable.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/verity/hash_algs.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/verity/open.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/locks.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/posix_acl.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/proc/inode.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/proc/base.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/ext4/super.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/fat/dir.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/fat/inode.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/fat/misc.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In block/bio.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In block/blk-core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In block/blk-mq.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In block/blk-rq-qos.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In block/blk-iocost.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In lib/llist.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In lib/errseq.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In lib/genalloc.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/irqchip/irq-mvebu-icu.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/amba/bus.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/xen/grant-table.c (ffff80001082c364)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access_ref_v1
```
```
In drivers/xen/events/events_fifo.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/tty/tty_ldsem.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/tty/serial/8250/8250_dw.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/tty/serial/8250/8250_mtk.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/base/core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/spi/spi-omap2-mcspi.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/i2c/busses/i2c-sprd.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/md/md.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/perf/arm-cci.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/perf/arm_pmu.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/perf/qcom_l2_pmu.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/perf/qcom_l3_pmu.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In drivers/perf/xgene_pmu.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/core/sock.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/core/skbuff.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/core/dst.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/core/neighbour.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/core/netpoll.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/core/dst_cache.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/route.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/protocol.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv6/route.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv6/ip6_icmp.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/ipv6/protocol.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In lib/dec_and_lock.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
Inline: True
```
```
In lib/dump_stack.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:377
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
