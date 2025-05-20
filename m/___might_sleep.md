# Function: <code>___might_sleep</code>

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
In arch/x86/xen/mmu.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In security/selinux/ss/mls.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In lib/radix-tree.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/mmc/core/mmc.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In drivers/mmc/core/sdio_ops.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:193
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:193
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
In arch/x86/xen/mmu.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In security/selinux/ss/mls.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In lib/radix-tree.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/mmc/core/mmc.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In drivers/mmc/core/sdio_ops.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:199
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:199
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
In arch/x86/xen/mmu.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In security/selinux/ss/mls.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/mmc/core/mmc.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In drivers/mmc/core/sdio_ops.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:204
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:204
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
In arch/x86/xen/mmu.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In security/selinux/ss/mls.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/mmc/core/mmc.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In drivers/mmc/core/sdio_ops.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:208
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:208
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
In arch/x86/xen/mmu.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In kernel/memremap.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In security/selinux/ss/mls.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/mmc/core/mmc.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In drivers/mmc/core/sdio_ops.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:230
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:230
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
In arch/x86/xen/mmu.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In kernel/memremap.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In security/selinux/ss/mls.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:231
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In kernel/memremap.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:264
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:264
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:237
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:237
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:256
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:247
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:247
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:247
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:148
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In security/selinux/ss/symtab.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kernel.h:148
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kernel.h:148
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:158
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In security/selinux/ss/symtab.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In security/landlock/fs.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kernel.h:158
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kernel.h:158
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:171
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In security/selinux/ss/symtab.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In security/landlock/fs.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In block/blk-exec.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kernel.h:171
Inline: True
```
</details>
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
In arch/arm64/kernel/sys_compat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/arm64/kernel/armv8_deprecated.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In virt/kvm/arm/arm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In virt/kvm/arm/mmu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:256
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
In arch/arm/kernel/traps.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/arm/kernel/swp_emulate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/mtd/nand/raw/nand_base.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/mtd/nand/raw/nand_legacy.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/mtd/nand/raw/omap2.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:256
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
In arch/powerpc/kernel/rtas.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/powerpc/kernel/fadump.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/powerpc/mm/mem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/powerpc/platforms/pseries/lpar.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/powerpc/platforms/pseries/mobility.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/vfio/vfio_iommu_spapr_tce.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:256
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
In kernel/softirq.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:256
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:256
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
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/nvdimm/btt.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:256
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/xen/preempt.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:256
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
</details>
</li>
</ul>

## Differences
