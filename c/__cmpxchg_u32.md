# Function: <code>__cmpxchg_u32</code>

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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/fadump.c (c00000000004d200)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - arch/powerpc/kernel/fadump.c:crash_fadump
```
```
In arch/powerpc/kernel/smp.c (c000000000054140)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:nmi_ipi_lock
  - arch/powerpc/kernel/smp.c:nmi_ipi_lock_start
```
```
In arch/powerpc/mm/book3s64/iommu_api.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In arch/powerpc/platforms/powernv/idle.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In arch/powerpc/xmon/xmon.c (c000000000109720)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:get_output_lock
  - arch/powerpc/xmon/xmon.c:get_output_lock
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c0000000001218ec)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_commence_exit
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_commence_exit
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_commence_exit
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c000000000123eb0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:kvmppc_deliver_irq_passthru
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_eoi
```
```
In kernel/panic.c (c00000000013c83c)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/exit.c (c0000000001422cc)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/task_work.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/smpboot.c (c000000000179390)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (c0000000001798e8)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/sched/psi.c (c0000000001bec44)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
```
```
In kernel/locking/rwsem.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/locking/osq_lock.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/printk/printk_safe.c (c0000000001d0454)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (c0000000001ebc98)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/acct.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/kexec_core.c (c000000000232414)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/debug/kdb/kdb_io.c (c00000000027548c)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/trace/ring_buffer.c (c000000000299410)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/trace/tracing_map.c (c0000000002b750c)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/irq_work.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/events/core.c (c000000000346f70)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In kernel/jump_label.c (c00000000035f664)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/oom_kill.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In mm/vmscan.c (c0000000003877fc)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/mmzone.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In mm/mmap.c (c0000000003d030c)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/page_alloc.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In mm/frontswap.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In mm/ksm.c (c00000000041fd60)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (c000000000439ac0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c000000000442d70)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (c000000000448ac0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In mm/cleancache.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In mm/memfd.c (c0000000004717dc)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (c000000000472a2c)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/exec.c (c0000000004847a4)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (c0000000004921d8)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/dcache.c (c0000000004a3748)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
```
```
In fs/inode.c (c0000000004a6660)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - fs/inode.c:inode_set_flags
```
```
In fs/fs-writeback.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/nsfs.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/buffer.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/direct-io.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/notify/mark.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/eventpoll.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/aio.c (c000000000502c9c)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In fs/io_uring.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/crypto/keysetup.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/verity/enable.c (c00000000051f600)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/verity/hash_algs.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/verity/open.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/locks.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/posix_acl.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/iomap/direct-io.c (c00000000053d994)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/proc/inode.c (c00000000054f498)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (c00000000056c370)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
```
```
In fs/ext4/dir.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/fat/dir.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/fat/inode.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/fat/misc.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/fuse/dir.c (c00000000064f2bc)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In block/bio.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In block/blk-mq.c (c00000000078702c)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (c00000000078bdf8)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (c0000000007a3be8)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-cgroup.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In block/blk-iocost.c (c0000000007b2370)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/llist.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In lib/errseq.c (c0000000007de3f0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - lib/errseq.c:errseq_check_and_advance
  - lib/errseq.c:errseq_set
```
```
In lib/genalloc.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In lib/sbitmap.c (c00000000081eb38)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (c0000000008941dc)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/tty/tty_ldsem.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In drivers/char/random.c (c000000000946fe0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/dma-buf/dma-fence-array.c (c000000000a1f9e4)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In drivers/vfio/vfio.c (c000000000aaeb7c)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (c000000000bbb774)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/md.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In drivers/md/dm.c (c000000000bf0848)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:alloc_dev
```
```
In net/core/sock.c (c000000000c84368)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/skbuff.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In net/core/dev.c (c000000000cb33a4)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/dst.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In net/core/filter.c (c000000000cde658)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/sock_diag.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In net/core/netpoll.c (c000000000cfd4e4)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/lwtunnel.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In net/ipv4/route.c (c000000000d57e58)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/protocol.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7aaa8)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In net/ipv6/route.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In net/ipv6/ip6_fib.c (c000000000e463f4)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In net/ipv6/ip6_icmp.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In net/ipv6/protocol.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
```
```
In lib/dump_stack.c (c000000000ec3dbc)
Location: arch/powerpc/include/asm/cmpxchg.h:223
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
</details>
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
