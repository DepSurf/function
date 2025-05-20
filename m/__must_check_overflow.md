# Function: <code>__must_check_overflow</code>

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
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/irq/devres.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/trace_events_synth.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/mempool.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/crypto/inline_crypt.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/squashfs/cache.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/security.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/selinux/ss/avtab.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/selinux/ss/conditional.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/keyslot-manager.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/mpi/mpi-mod.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/mpi/mpiutil.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/argv_split.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/memcat_p.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pinctrl/pinctrl-utils.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/x86/s2idle.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/acpi_adxl.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/fan.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/clk/clk-bulk.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/agp/isoch.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/tpm/eventlog/tpm2.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/component.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/map.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/swnode.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/misc/sram.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/mfd/twl-core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/net/phy/phy_led_triggers.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/quirks.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/platform/x86/intel_pmc_core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/mailbox/pcc.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/netlink/policy.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ethtool/common.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ethtool/strset.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/overflow.h:52
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
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/irq/devres.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/trace_events_synth.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/mempool.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/crypto/inline_crypt.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/squashfs/cache.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/security.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/selinux/ss/avtab.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/selinux/ss/conditional.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/keyslot-manager.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/mpi/mpi-mod.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/mpi/mpiutil.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/argv_split.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In lib/memcat_p.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pinctrl/pinctrl-utils.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/x86/s2idle.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/acpi_adxl.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/fan.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/clk/clk-bulk.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/agp/isoch.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/char/tpm/eventlog/tpm2.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/component.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/map.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/swnode.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/misc/sram.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/mfd/twl-core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/net/phy/phy_led_triggers.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/core/quirks.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/mmc/core/host.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/platform/x86/intel_pmc_core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/mailbox/pcc.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/netlink/policy.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ethtool/common.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ethtool/strset.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/linux/overflow.h:52
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/overflow.h:52
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
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/devres.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/msi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_eprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_synth.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/mempool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/crypto/inline_crypt.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/squashfs/cache.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/security.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/avtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/conditional.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/keyslot-manager.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/mpi/mpi-mod.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/mpi/mpiutil.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/argv_split.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/memcat_p.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/pinctrl-utils.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/x86/s2idle.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/prmt.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_adxl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/fan.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/clk/clk-bulk.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/agp/isoch.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/tpm/eventlog/tpm2.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/component.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/swnode.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/misc/sram.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mfd/twl-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/phy/phy_led_triggers.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/quirks.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mmc/core/host.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mailbox/pcc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlink/policy.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/strset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/overflow.h:49
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
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/hyperv/ivm.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/irq/devres.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/irq/msi.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/dma/remap.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/module/sysfs.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/trace_eprobe.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/trace_events_synth.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/bloom_filter.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/reuseport_array.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/mempool.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/crypto/inline_crypt.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/squashfs/cache.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/security.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/selinux/ss/avtab.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/selinux/ss/conditional.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/apparmor/policy_compat.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/blk-ia-ranges.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/blk-crypto-profile.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/string_helpers.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/assoc_array.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/mpi/mpi-mod.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/mpi/mpiutil.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/stackdepot.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/argv_split.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In lib/memcat_p.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/pinctrl/pinctrl-utils.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/x86/s2idle.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/prmt.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/acpi_adxl.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/fan_core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/clk/clk-bulk.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/char/agp/isoch.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/char/tpm/eventlog/tpm2.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/component.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/map.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/swnode.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/misc/sram.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/mfd/twl-core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/net/phy/phy_led_triggers.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/core/quirks.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/mmc/core/host.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/mailbox/pcc.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In drivers/hte/hte.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/netlink/policy.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ethtool/common.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ethtool/strset.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/linux/overflow.h:50
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/overflow.h:50
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
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/hyperv/ivm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/platform/efi/runtime-map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/devres.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/msi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/dma/remap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/module/sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_eprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_synth.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/bloom_filter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/reuseport_array.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/mempool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/squashfs/cache.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/security.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/avtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/conditional.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/policy_compat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-ia-ranges.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-crypto-profile.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/filetable.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/net.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/kbuf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/string_helpers.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/assoc_array.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/mpi/mpi-mod.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/mpi/mpiutil.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/stackdepot.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/pinctrl-utils.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/scan.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/property.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/x86/s2idle.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/prmt.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_adxl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/fan_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/clk/clk-bulk.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma/hsu/hsu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/regulator/devres.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/agp/isoch.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/tpm/eventlog/tpm2.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/component.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/swnode.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/misc/sram.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mfd/twl-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/phy/phy_led_triggers.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/quirks.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mmc/core/host.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mailbox/pcc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/hte/hte.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlink/policy.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/strset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/argv_split.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/memcat_p.c (0)
Location: include/linux/overflow.h:49
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
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/platform/efi/runtime-map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/devres.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/msi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/dma/remap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/module/decompress.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/module/sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_eprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_synth.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_fprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/bloom_filter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/reuseport_array.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/mempool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/verity/open.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/squashfs/cache.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/security.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/avtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/conditional.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/policy_compat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-ia-ranges.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-crypto-profile.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/filetable.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/net.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/kbuf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/string_helpers.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/assoc_array.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/mpi/mpi-mod.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/mpi/mpiutil.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/stackdepot.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/group_cpus.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/pinctrl-utils.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/scan.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/property.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/x86/s2idle.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/prmt.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_adxl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/fan_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/clk/clk-bulk.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma/hsu/hsu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/regulator/devres.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/agp/isoch.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/tpm/eventlog/tpm2.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/intel/perfmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/component.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/swnode.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache-maple.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/soc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/misc/sram.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mfd/twl-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/scsi/virtio_scsi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/phy/phy_led_triggers.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/quirks.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mmc/core/host.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mailbox/pcc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/hte/hte.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlink/policy.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/strset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/devlink/leftover.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/handshake/request.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/argv_split.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/memcat_p.c (0)
Location: include/linux/overflow.h:49
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
In init/do_mounts.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/platform/efi/runtime-map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/resource.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/params.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/devres.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/msi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/dma/remap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/module/decompress.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/module/sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_eprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_synth.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_btf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/trace/trace_fprobe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/bloom_filter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/reuseport_array.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/mempool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In mm/page_reporting.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/verity/open.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/squashfs/cache.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In fs/tracefs/event_inode.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/security.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/ebitmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/avtab.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/ss/conditional.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/apparmor/policy_compat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In security/integrity/ima/ima_modsig.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-ia-ranges.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-crypto-profile.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/filetable.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/net.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/kbuf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/register.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In io_uring/futex.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/string_helpers.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/crypto/mpi/mpi-mod.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/crypto/mpi/mpiutil.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/assoc_array.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/stackdepot.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/group_cpus.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/pinctrl-utils.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/utils.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/scan.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/mipi-disco-img.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/property.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/x86/s2idle.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/prmt.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/acpi_adxl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/fan_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/clk/clk-bulk.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma/hsu/hsu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/regulator/devres.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/agp/isoch.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/char/tpm/eventlog/tpm2.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/intel/perfmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/component.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/map.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/swnode.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regcache-maple.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/base/soc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/misc/sram.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mfd/twl-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/scsi/virtio_scsi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_atomic.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_blend.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_client_modeset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_color_mgmt.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_crtc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_edid.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_framebuffer.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_gem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_lease.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_managed.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_plane.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_property.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_syncobj.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_vblank.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_debugfs_crc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_crtc_helper.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_damage_helper.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/gpu/drm/drm_plane_helper.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/phy/phy_led_triggers.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/core/quirks.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/gov_power_allocator.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mmc/core/host.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/platform/x86/amd/wbrf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/mailbox/pcc.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In drivers/hte/hte.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlink/policy.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/common.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/strset.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/tcp_sigpool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/devlink/netlink.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/devlink/linecard.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In net/handshake/request.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/pci/irq.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/argv_split.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/memcat_p.c (0)
Location: include/linux/overflow.h:49
Inline: True
```
```
In lib/objpool.c (0)
Location: include/linux/overflow.h:49
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
