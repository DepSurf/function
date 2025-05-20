# Function: <code>task_thread_info</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/cgroup.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/compat.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:3180
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:3180
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
In arch/x86/entry/common.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1426
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1426
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
In arch/x86/entry/common.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1456
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1456
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
In arch/x86/entry/common.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8110c391)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1567
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1567
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
In arch/x86/entry/common.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81117b81)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1580
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1580
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
In arch/x86/entry/common.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1653
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1653
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
In arch/x86/entry/common.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1646
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
In arch/x86/entry/common.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1688
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/sched.h:1688
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
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/sched.h:1749
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/sched.h:1749
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
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/sched.h:1771
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/sched.h:1771
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
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/sched.h:1888
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/sched.h:1888
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
In arch/arm64/kernel/debug-monitors.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/arm64/kernel/fpsimd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/arm64/kernel/process.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/arm64/kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/arm64/kernel/sys_compat.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/arm64/kernel/perf_regs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/arm64/kernel/hw_breakpoint.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/arm64/kernel/armv8_deprecated.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/arm64/kernel/ssbd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/arm64/mm/fault.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In virt/kvm/kvm_main.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In virt/kvm/arm/arm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mmu_context.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/misc/vexpress-syscfg.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/firmware/efi/arm-runtime.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
</details>
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
In arch/powerpc/kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/powerpc/kernel/process.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/powerpc/kernel/setup-common.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/powerpc/mm/fault.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/powerpc/mm/mmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/powerpc/mm/book3s64/slb.c (c00000000008f4e0)
Location: include/linux/sched.h:1646
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/slb.c:switch_slb
```
```
In arch/powerpc/mm/book3s64/radix_hugetlbpage.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/powerpc/mm/slice.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/powerpc/platforms/pseries/smp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/powerpc/perf/callchain.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/powerpc/perf/perf_regs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mmu_gather.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In lib/syscall.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1646
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
In arch/riscv/kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/riscv/mm/fault.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1646
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
In arch/x86/entry/common.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1646
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
In arch/x86/entry/common.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/context_tracking.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1646
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
In arch/x86/entry/common.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/netfilter/nfnetlink.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1646
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
In arch/x86/entry/common.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/cpu/bugs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/wait_bit.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/swait.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/freezer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/user-return-notifier.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/tty_port.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/sched.h:1646
Inline: True
```
</details>
</li>
</ul>

## Differences
