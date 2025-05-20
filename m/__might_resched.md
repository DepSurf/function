# Function: <code>__might_resched</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/kallsyms.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mmu_gather.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:182
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In security/selinux/ss/symtab.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In security/landlock/fs.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kernel.h:182
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/kallsyms.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mmu_gather.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:182
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In security/selinux/ss/symtab.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In security/landlock/fs.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In io_uring/tctx.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In io_uring/kbuf.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kernel.h:182
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kernel.h:182
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/kallsyms.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/mmu_gather.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:183
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In security/selinux/ss/symtab.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In security/landlock/fs.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In io_uring/tctx.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In io_uring/kbuf.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kernel.h:183
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kernel.h:183
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/kallsyms.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/shrinker.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/mmu_gather.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In security/selinux/ss/symtab.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In security/landlock/fs.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In io_uring/tctx.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In io_uring/kbuf.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In lib/crypto/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/gpu/drm/drm_gem.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kernel.h:179
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kernel.h:179
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
