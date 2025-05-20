# Function: <code>kmsan_copy_to_user</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/signal_64.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/signal_32.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In mm/maccess.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: False
```
```
In lib/usercopy.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: False
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kmsan-checks.h:76
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
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/signal_64.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/signal_32.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/log.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In mm/maccess.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: False
```
```
In lib/usercopy.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: False
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kmsan-checks.h:76
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
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/signal_64.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/signal_32.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In arch/x86/kernel/shstk.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/log.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In mm/maccess.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In security/lsm_syscalls.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In security/security.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In io_uring/waitid.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: False
```
```
In lib/usercopy.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: False
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/video/fbdev/core/fb_chrdev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/gpu/drm/drm_connector.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/gpu/drm/drm_lease.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/gpu/drm/drm_mode_config.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/gpu/drm/drm_mode_object.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/gpu/drm/drm_plane.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/gpu/drm/drm_property.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/gpu/drm/drm_ioc32.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kmsan-checks.h:76
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kmsan-checks.h:76
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
