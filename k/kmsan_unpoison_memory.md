# Function: <code>kmsan_unpoison_memory</code>

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
In arch/x86/kernel/head64.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/entry/common.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/signal_64.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/signal_32.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/maccess.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In io_uring/net.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In lib/iomap.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
```
```
In lib/strnlen_user.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
```
```
In arch/x86/lib/iomem.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
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
In arch/x86/entry/common.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/head64.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/signal_64.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/signal_32.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/maccess.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In io_uring/net.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In lib/iomap.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
```
```
In lib/strnlen_user.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
```
```
In lib/stackdepot.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/lib/iomem.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
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
In arch/x86/entry/common.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/head64.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/signal_64.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/signal_32.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/sev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/kernel/shstk.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/maccess.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In security/lsm_syscalls.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In security/security.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In io_uring/net.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In lib/iomap.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
```
```
In lib/strnlen_user.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
```
```
In lib/stackdepot.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/lib/iomem.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/gpu/drm/drm_crtc.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/kmsan-checks.h:70
Inline: False
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
