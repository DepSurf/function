# Function: <code>might_fault</code>

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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/time/timer_stats.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/compat.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In ipc/compat_mq.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In security/integrity/evm/evm_secfs.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In lib/dynamic_debug.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/pinctrl/pinconf.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/netfilter/nf_log.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/kernel.h:250
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/kernel.h:250
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/time/timer_stats.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/kexec.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/relay.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/filesystems.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/seq_file.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/xattr.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/compat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/quota/quota.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/dcookies.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In ipc/compat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In ipc/shm.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In ipc/compat_mq.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/keys/user_defined.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/keys/dh.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/keys/big_key.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/keys/trusted.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In security/integrity/evm/evm_secfs.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In lib/kstrtox.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/pinctrl/pinconf.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/kernel.h:256
Inline: False
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
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: False
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
In net/core/scm.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:256
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/kernel.h:256
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/kernel.h:256
Inline: False
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/time/timer_stats.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/kexec.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/relay.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/dcache.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/filesystems.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/seq_file.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/xattr.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/locks.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/compat.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/quota/quota.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/dcookies.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/pstore/platform.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In ipc/compat.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In ipc/shm.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In ipc/compat_mq.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/keys/user_defined.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/keys/dh.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/keys/big_key.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/keys/trusted.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In security/integrity/evm/evm_secfs.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In lib/seq_buf.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In lib/kstrtox.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/pinctrl/pinconf.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:261
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/kernel.h:261
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/kernel.h:261
Inline: False
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kernel.h:265
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:265
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:265
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:265
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/kernel.h:265
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:265
Inline: False
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In security/security.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:265
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:265
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kernel.h:287
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:287
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:287
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:287
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/kernel.h:287
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:287
Inline: False
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In security/security.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:287
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:287
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kernel.h:288
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:288
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:288
Inline: False
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:288
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/kernel.h:288
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:288
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:288
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:288
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kernel.h:321
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:321
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:321
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/kernel.h:321
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:321
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:321
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:321
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:295
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:295
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:316
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:314
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:314
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:314
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:314
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:314
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:167
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:167
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In arch/x86/kernel/sev-es.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:167
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:167
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:167
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:177
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:177
Inline: False
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:177
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:177
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:177
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:190
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/sched/core_sched.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:190
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:190
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:190
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:200
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:200
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/kernel.h:200
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/kernel.h:200
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:200
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kernel.h:200
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:200
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kernel.h:200
Inline: False
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kernel.h:200
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kernel.h:200
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:200
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kernel.h:200
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/kernel.h:200
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/kernel.h:201
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:201
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kernel.h:201
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/bpf/log.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:201
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kernel.h:201
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kernel.h:201
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:201
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kernel.h:201
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kernel.h:201
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/kernel.h:201
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/kernel.h:197
Inline: False
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:197
Inline: False
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In arch/x86/kernel/shstk.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/futex/pi.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/futex/requeue.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/futex/waitwake.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kernel.h:197
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/bpf/log.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:197
Inline: False
```
```
In fs/file.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kernel.h:197
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kernel.h:197
Inline: False
```
```
In security/lsm_syscalls.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In security/security.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/video/fbdev/core/fb_chrdev.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:197
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/gpu/drm/drm_connector.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/gpu/drm/drm_crtc.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/gpu/drm/drm_lease.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/gpu/drm/drm_mode_config.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/gpu/drm/drm_mode_object.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/gpu/drm/drm_plane.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/gpu/drm/drm_property.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/gpu/drm/drm_ioc32.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kernel.h:197
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/kernel.h:197
Inline: True
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/kernel.h:197
Inline: True
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
In arch/arm64/kernel/debug-monitors.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/arm64/kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/arm64/kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/arm64/kernel/traps.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/arm64/kernel/signal32.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/arm64/kernel/crash_dump.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In virt/kvm/kvm_main.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In virt/kvm/vfio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In virt/kvm/arm/arm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In virt/kvm/arm/psci.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/arm64/kvm/guest.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/arm64/kvm/sys_regs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-kvm-device.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-its.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In virt/kvm/arm/arch_timer.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In virt/kvm/arm/pmu.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/maccess.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/checksum.c (0)
Location: include/linux/kernel.h:316
Inline: False
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/strnlen_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pci/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/edac/altera_edac.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/kernel.h:316
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
In arch/arm/kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/arm/kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/arm/kernel/traps.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/arm/kernel/machine_kexec.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/arm/kernel/crash_dump.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/arm/mm/alignment.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/maccess.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/binfmt_elf_fdpic.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/binfmt_flat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/pstore/ram_core.c (0)
Location: include/linux/kernel.h:316
Inline: False
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/strnlen_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pci/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/mtd/mtdchar.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/ethernet/ti/cpsw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/musb/musb_debugfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/rtc/rtc-pcf8523.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/firmware/tegra/bpmp-debugfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In sound/core/memory.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In sound/core/control.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In sound/core/info.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In sound/core/timer.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In sound/core/pcm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In sound/core/pcm_native.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In sound/core/pcm_lib.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In sound/core/compress_offload.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In sound/soc/soc-generic-dmaengine-pcm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/kernel.h:316
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
In arch/powerpc/kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/kernel/align.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/kernel/signal_32.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/kernel/process.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/kernel/traps.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/kernel/signal_64.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/kernel/ptrace32.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/kernel/vecemu.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/kernel/kvm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/mm/fault.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/lib/pmem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/lib/checksum_wrappers.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/lib/sstep.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-lpc.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-xscom.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/maccess.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/strnlen_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pci/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:316
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
Location: include/linux/kernel.h:316
Inline: False
```
```
In arch/riscv/kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:316
Inline: False
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/binfmt_flat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/checksum.c (0)
Location: include/linux/kernel.h:316
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:316
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:316
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:316
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:316
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/uid16.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/nsfs.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/quota/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/kernel.h:316
Inline: True
```
</details>
</li>
</ul>

## Differences
