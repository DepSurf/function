# Function: <code>copy_overflow</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/ptrace.c (ffffffff81090b82)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/sys.c (ffffffff810982bf)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:SyS_setdomainname
  - kernel/sys.c:SyS_sethostname
```
```
In kernel/sched/core.c (ffffffff810ac450)
Location: include/linux/thread_info.h:121
Inline: True
Direct callers:
  - kernel/sched/core.c:SyS_sched_getattr
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/printk/printk.c (ffffffff810e1e90)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/futex.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/compat.c (ffffffff811211b6)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - kernel/compat.c:C_SYSC_migrate_pages
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81160a50)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In kernel/bpf/syscall.c (ffffffff81191780)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In kernel/events/core.c (ffffffff8119fac0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In mm/mempolicy.c (ffffffff8121e38f)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - mm/mempolicy.c:C_SYSC_mbind
  - mm/mempolicy.c:C_SYSC_set_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/seq_file.c (ffffffff8127af53)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/xattr.c (ffffffff8127b590)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/libfs.c (ffffffff8127d260)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129c66b)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/binfmt_elf.c (ffffffff812b4740)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff812b76e0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/fhandle.c (ffffffff812bd8a0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/proc/base.c (ffffffff812c9bc0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/kernfs/file.c (ffffffff812dba20)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/fat/dir.c (ffffffff81353d90)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In fs/ecryptfs/miscdev.c (ffffffff8136aed1)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/debugfs/file.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In ipc/sem.c (ffffffff813858c0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In security/keys/keyctl.c (ffffffff81391050)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In security/keys/dh.c (ffffffff8139662f)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In security/keys/big_key.c (ffffffff81396af0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/security.c (ffffffff8139fe64)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - security/security.c:security_task_prctl
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In security/integrity/evm/evm_secfs.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In block/scsi_ioctl.c (ffffffff814430a0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In block/bsg.c (ffffffff81443f10)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/pinctrl/pinconf.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e82f0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff814ecc60)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff815758a0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/tty/vt/keyboard.c (ffffffff81586cab)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/char/random.c (ffffffff815a86f2)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (ffffffff815ac4ad)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff8162d3a0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81644df0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/net/tun.c (ffffffff81695260)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff816bcde0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In drivers/md/dm.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff817540b0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/socket.c (ffffffff817ad2f0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/core/sock.c (ffffffff817b651e)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff817c6e2f)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffffffff817d3dc0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/core/filter.c (ffffffff817e9070)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/compat.c (ffffffff817fb259)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/bpf/test_run.c (ffffffff8180c660)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181c0e9)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff818222e0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81845780)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a1920)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/ipv6/udp.c (ffffffff818a7d00)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff818c3fb2)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff818d5974)
Location: include/linux/thread_info.h:121
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffffffff818d6430)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/wireless/wext-priv.c (ffffffff818d7b50)
Location: include/linux/thread_info.h:121
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:121
Inline: True
```
**Symbols:**

```
ffffffff810ac450-ffffffff810ac469: copy_overflow (STB_LOCAL)
ffffffff810e1e90-ffffffff810e1ea9: copy_overflow (STB_LOCAL)
ffffffff81160a50-ffffffff81160a69: copy_overflow (STB_LOCAL)
ffffffff81191780-ffffffff81191799: copy_overflow (STB_LOCAL)
ffffffff8119fac0-ffffffff8119fad9: copy_overflow (STB_LOCAL)
ffffffff8121aa70-ffffffff8121aa89: copy_overflow (STB_LOCAL)
ffffffff8127af53-ffffffff8127af6c: copy_overflow (STB_LOCAL)
ffffffff8127b590-ffffffff8127b5a9: copy_overflow (STB_LOCAL)
ffffffff8127d260-ffffffff8127d279: copy_overflow (STB_LOCAL)
ffffffff812b4740-ffffffff812b4759: copy_overflow (STB_LOCAL)
ffffffff812b76e0-ffffffff812b76f9: copy_overflow (STB_LOCAL)
ffffffff812bd8a0-ffffffff812bd8b9: copy_overflow (STB_LOCAL)
ffffffff812c9bc0-ffffffff812c9bd9: copy_overflow (STB_LOCAL)
ffffffff812dba20-ffffffff812dba39: copy_overflow (STB_LOCAL)
ffffffff81353d90-ffffffff81353da9: copy_overflow (STB_LOCAL)
ffffffff813858c0-ffffffff813858d9: copy_overflow (STB_LOCAL)
ffffffff81391050-ffffffff81391069: copy_overflow (STB_LOCAL)
ffffffff8139662f-ffffffff81396648: copy_overflow (STB_LOCAL)
ffffffff81396af0-ffffffff81396b09: copy_overflow (STB_LOCAL)
ffffffff814430a0-ffffffff814430b9: copy_overflow (STB_LOCAL)
ffffffff81443f10-ffffffff81443f29: copy_overflow (STB_LOCAL)
ffffffff814e82f0-ffffffff814e8309: copy_overflow (STB_LOCAL)
ffffffff814ecc60-ffffffff814ecc79: copy_overflow (STB_LOCAL)
ffffffff815758a0-ffffffff815758b9: copy_overflow (STB_LOCAL)
ffffffff81586cab-ffffffff81586cc4: copy_overflow (STB_LOCAL)
ffffffff815ac4ad-ffffffff815ac4c6: copy_overflow (STB_LOCAL)
ffffffff8162d3a0-ffffffff8162d3b9: copy_overflow (STB_LOCAL)
ffffffff81644df0-ffffffff81644e09: copy_overflow (STB_LOCAL)
ffffffff81695260-ffffffff8169527c: copy_overflow.constprop.62 (STB_LOCAL)
ffffffff816bcde0-ffffffff816bcdf9: copy_overflow (STB_LOCAL)
ffffffff817540b0-ffffffff817540c9: copy_overflow (STB_LOCAL)
ffffffff817ad2f0-ffffffff817ad309: copy_overflow (STB_LOCAL)
ffffffff817b2790-ffffffff817b27a9: copy_overflow (STB_LOCAL)
ffffffff817d3dc0-ffffffff817d3dd9: copy_overflow (STB_LOCAL)
ffffffff817e9070-ffffffff817e9089: copy_overflow (STB_LOCAL)
ffffffff817f9b90-ffffffff817f9ba9: copy_overflow (STB_LOCAL)
ffffffff8180c660-ffffffff8180c679: copy_overflow (STB_LOCAL)
ffffffff818222e0-ffffffff818222f9: copy_overflow (STB_LOCAL)
ffffffff81845780-ffffffff81845799: copy_overflow (STB_LOCAL)
ffffffff818a1920-ffffffff818a1939: copy_overflow (STB_LOCAL)
ffffffff818a7d00-ffffffff818a7d19: copy_overflow (STB_LOCAL)
ffffffff818cef20-ffffffff818cef39: copy_overflow (STB_LOCAL)
ffffffff818d6430-ffffffff818d6449: copy_overflow (STB_LOCAL)
ffffffff818d7b50-ffffffff818d7b69: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In arch/x86/kernel/umip.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/sysctl.c (ffffffff81093e97)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_put_long
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/ptrace.c (ffffffff810979f2)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/sys.c (ffffffff8109ef8f)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:SyS_setdomainname
  - kernel/sys.c:SyS_sethostname
```
```
In kernel/sched/core.c (ffffffff810b3230)
Location: include/linux/thread_info.h:125
Inline: True
Direct callers:
  - kernel/sched/core.c:SyS_sched_getattr
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/printk/printk.c (ffffffff810e97b0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/futex.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/compat.c (ffffffff8112c826)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - kernel/compat.c:C_SYSC_migrate_pages
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8116db10)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/bpf/syscall.c (ffffffff8119e6d0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In kernel/events/core.c (ffffffff811b4570)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In mm/mempolicy.c (ffffffff812395df)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - mm/mempolicy.c:C_SYSC_mbind
  - mm/mempolicy.c:C_SYSC_set_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/seq_file.c (ffffffff8129d9bf)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/xattr.c (ffffffff8129e030)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/libfs.c (ffffffff8129ffe0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812bfae2)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/binfmt_elf.c (ffffffff812d7f80)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff812daf90)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/fhandle.c (ffffffff812e1170)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff812ea190)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/proc/base.c (ffffffff812ee450)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/kernfs/file.c (ffffffff81300340)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/fat/dir.c (ffffffff813789b0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In fs/ecryptfs/miscdev.c (ffffffff8138fa71)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/debugfs/file.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In ipc/sem.c (ffffffff813aa140)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In security/keys/keyctl.c (ffffffff813b6650)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In security/keys/dh.c (ffffffff813bbdbf)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In security/keys/big_key.c (ffffffff813bbf20)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In security/security.c (ffffffff813c5aa9)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - security/security.c:security_task_prctl
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In block/scsi_ioctl.c (ffffffff8146fb30)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In block/bsg.c (ffffffff814709a0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In block/compat_ioctl.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/pinctrl/pinconf.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151d400)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff815217e0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff815da930)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/tty/vt/keyboard.c (ffffffff815eb7ab)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/char/random.c (ffffffff8160eff5)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (ffffffff81612e6d)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff81695b50)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816add80)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/net/tun.c (ffffffff816ffd40)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817287b0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In drivers/md/dm.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff817c62e0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/socket.c (ffffffff81825310)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/core/sock.c (ffffffff8182eae4)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff818409fd)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffffffff8184e7a0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/core/filter.c (ffffffff81864460)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/compat.c (ffffffff81878bde)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/bpf/test_run.c (ffffffff8188b640)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189b03f)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff818a13e0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/ipv4/raw.c (ffffffff818c31e0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c51e0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81924290)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/ipv6/udp.c (ffffffff8192a7c0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8192e370)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81947242)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff8195a93a)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffffffff8195c2d0)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/wireless/wext-priv.c (ffffffff8195d730)
Location: include/linux/thread_info.h:125
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:125
Inline: True
```
**Symbols:**

```
ffffffff81093600-ffffffff81093619: copy_overflow (STB_LOCAL)
ffffffff810b3230-ffffffff810b3249: copy_overflow (STB_LOCAL)
ffffffff810e97b0-ffffffff810e97c9: copy_overflow (STB_LOCAL)
ffffffff8116db10-ffffffff8116db29: copy_overflow (STB_LOCAL)
ffffffff8119e6d0-ffffffff8119e6e9: copy_overflow (STB_LOCAL)
ffffffff811b4570-ffffffff811b4589: copy_overflow (STB_LOCAL)
ffffffff81235cc0-ffffffff81235cd9: copy_overflow (STB_LOCAL)
ffffffff8129d9bf-ffffffff8129d9d8: copy_overflow (STB_LOCAL)
ffffffff8129e030-ffffffff8129e049: copy_overflow (STB_LOCAL)
ffffffff8129ffe0-ffffffff8129fff9: copy_overflow (STB_LOCAL)
ffffffff812d7f80-ffffffff812d7f99: copy_overflow (STB_LOCAL)
ffffffff812daf90-ffffffff812dafa9: copy_overflow (STB_LOCAL)
ffffffff812e1170-ffffffff812e1189: copy_overflow (STB_LOCAL)
ffffffff812ea190-ffffffff812ea1a9: copy_overflow (STB_LOCAL)
ffffffff812ee450-ffffffff812ee469: copy_overflow (STB_LOCAL)
ffffffff81300340-ffffffff81300359: copy_overflow (STB_LOCAL)
ffffffff813789b0-ffffffff813789c9: copy_overflow (STB_LOCAL)
ffffffff813aa140-ffffffff813aa159: copy_overflow (STB_LOCAL)
ffffffff813b6650-ffffffff813b6669: copy_overflow (STB_LOCAL)
ffffffff813bbdbf-ffffffff813bbdd8: copy_overflow (STB_LOCAL)
ffffffff813bbf20-ffffffff813bbf39: copy_overflow (STB_LOCAL)
ffffffff8146fb30-ffffffff8146fb49: copy_overflow (STB_LOCAL)
ffffffff814709a0-ffffffff814709b9: copy_overflow (STB_LOCAL)
ffffffff8151d400-ffffffff8151d419: copy_overflow (STB_LOCAL)
ffffffff815217e0-ffffffff815217f9: copy_overflow (STB_LOCAL)
ffffffff815da930-ffffffff815da949: copy_overflow (STB_LOCAL)
ffffffff815eb7ab-ffffffff815eb7c4: copy_overflow (STB_LOCAL)
ffffffff81612e6d-ffffffff81612e86: copy_overflow (STB_LOCAL)
ffffffff81695b50-ffffffff81695b69: copy_overflow (STB_LOCAL)
ffffffff816add80-ffffffff816add99: copy_overflow (STB_LOCAL)
ffffffff816ffd40-ffffffff816ffd5c: copy_overflow.constprop.75 (STB_LOCAL)
ffffffff817287b0-ffffffff817287c9: copy_overflow (STB_LOCAL)
ffffffff817c62e0-ffffffff817c62f9: copy_overflow (STB_LOCAL)
ffffffff81825310-ffffffff81825329: copy_overflow (STB_LOCAL)
ffffffff8182a9e0-ffffffff8182a9f9: copy_overflow (STB_LOCAL)
ffffffff8184e7a0-ffffffff8184e7b9: copy_overflow (STB_LOCAL)
ffffffff81864460-ffffffff81864479: copy_overflow (STB_LOCAL)
ffffffff818774a0-ffffffff818774b9: copy_overflow (STB_LOCAL)
ffffffff8188b640-ffffffff8188b659: copy_overflow (STB_LOCAL)
ffffffff818a13e0-ffffffff818a13f9: copy_overflow (STB_LOCAL)
ffffffff818c31e0-ffffffff818c31f9: copy_overflow (STB_LOCAL)
ffffffff818c51e0-ffffffff818c51f9: copy_overflow (STB_LOCAL)
ffffffff81924290-ffffffff819242a9: copy_overflow (STB_LOCAL)
ffffffff8192a7c0-ffffffff8192a7d9: copy_overflow (STB_LOCAL)
ffffffff8192e370-ffffffff8192e389: copy_overflow (STB_LOCAL)
ffffffff81953eb0-ffffffff81953ec9: copy_overflow (STB_LOCAL)
ffffffff8195c2d0-ffffffff8195c2e9: copy_overflow (STB_LOCAL)
ffffffff8195d730-ffffffff8195d749: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/umip.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/sysctl.c (ffffffff81097060)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/ptrace.c (ffffffff8109b302)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff8109d2e4)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810a4865)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/core.c (ffffffff810ba340)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (ffffffff810f1a80)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/futex.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8117c970)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811b2f30)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff811c77f0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/sockmap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mempolicy.c (ffffffff8125b626)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (ffffffff812c46f0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/libfs.c (ffffffff812c6790)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e95c1)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/binfmt_elf.c (ffffffff81303050)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff81306730)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fat/dir.c (ffffffff813a74d0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ecryptfs/miscdev.c (ffffffff813bea67)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/sem.c (ffffffff813d9300)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/keyctl.c (ffffffff813e6e50)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/dh.c (ffffffff813ec230)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/big_key.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/scsi_ioctl.c (ffffffff814a3ea0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (ffffffff814a4c10)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/pinctrl/pinconf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff81557470)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff81613a50)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/keyboard.c (ffffffff81621650)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (ffffffff81648b04)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (ffffffff81649b40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff816d1c10)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816ea180)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/net/tun.c (ffffffff8173bb30)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81767600)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm.c (ffffffff81806ae0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm-ioctl.c (ffffffff8180f080)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/socket.c (ffffffff8186f2c0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (ffffffff81874b40)
Location: include/linux/thread_info.h:132
Inline: True
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff8188b0b4)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffffffff81899570)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (ffffffff818b1620)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/compat.c (ffffffff818ca0a7)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (ffffffff818df0a0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef567)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff818f5f00)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/raw.c (ffffffff81918ce0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191abb0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197c720)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/udp.c (ffffffff81982ae0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81987010)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819a024a)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff819b25be)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffffffff819b5b20)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/wireless/wext-priv.c (ffffffff819b6f70)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
**Symbols:**

```
ffffffff81097060-ffffffff81097079: copy_overflow (STB_LOCAL)
ffffffff810ba340-ffffffff810ba359: copy_overflow (STB_LOCAL)
ffffffff810f1a80-ffffffff810f1a99: copy_overflow (STB_LOCAL)
ffffffff8117c970-ffffffff8117c989: copy_overflow (STB_LOCAL)
ffffffff811b2f30-ffffffff811b2f49: copy_overflow (STB_LOCAL)
ffffffff811c77f0-ffffffff811c7809: copy_overflow (STB_LOCAL)
ffffffff812c46f0-ffffffff812c4709: copy_overflow (STB_LOCAL)
ffffffff812c6790-ffffffff812c67a9: copy_overflow (STB_LOCAL)
ffffffff81303050-ffffffff81303069: copy_overflow (STB_LOCAL)
ffffffff81306730-ffffffff81306749: copy_overflow (STB_LOCAL)
ffffffff813a74d0-ffffffff813a74e9: copy_overflow (STB_LOCAL)
ffffffff813d9300-ffffffff813d9319: copy_overflow (STB_LOCAL)
ffffffff813e6e50-ffffffff813e6e69: copy_overflow (STB_LOCAL)
ffffffff813ec230-ffffffff813ec249: copy_overflow (STB_LOCAL)
ffffffff814a3ea0-ffffffff814a3eb9: copy_overflow (STB_LOCAL)
ffffffff814a4c10-ffffffff814a4c29: copy_overflow (STB_LOCAL)
ffffffff81557470-ffffffff81557489: copy_overflow (STB_LOCAL)
ffffffff81613a50-ffffffff81613a69: copy_overflow (STB_LOCAL)
ffffffff81621650-ffffffff81621669: copy_overflow (STB_LOCAL)
ffffffff81649b40-ffffffff81649b59: copy_overflow (STB_LOCAL)
ffffffff816d1c10-ffffffff816d1c29: copy_overflow (STB_LOCAL)
ffffffff816ea180-ffffffff816ea199: copy_overflow (STB_LOCAL)
ffffffff8173bb30-ffffffff8173bb49: copy_overflow (STB_LOCAL)
ffffffff81767600-ffffffff81767619: copy_overflow (STB_LOCAL)
ffffffff81806ae0-ffffffff81806af9: copy_overflow (STB_LOCAL)
ffffffff8180f080-ffffffff8180f099: copy_overflow (STB_LOCAL)
ffffffff8186f2c0-ffffffff8186f2d9: copy_overflow (STB_LOCAL)
ffffffff81874b40-ffffffff81874b59: copy_overflow (STB_LOCAL)
ffffffff81899570-ffffffff81899589: copy_overflow (STB_LOCAL)
ffffffff818b1620-ffffffff818b1639: copy_overflow (STB_LOCAL)
ffffffff818df0a0-ffffffff818df0b9: copy_overflow (STB_LOCAL)
ffffffff818f5f00-ffffffff818f5f19: copy_overflow (STB_LOCAL)
ffffffff81918ce0-ffffffff81918cf9: copy_overflow (STB_LOCAL)
ffffffff8191abb0-ffffffff8191abc9: copy_overflow (STB_LOCAL)
ffffffff8197c720-ffffffff8197c739: copy_overflow (STB_LOCAL)
ffffffff81982ae0-ffffffff81982af9: copy_overflow (STB_LOCAL)
ffffffff81987010-ffffffff81987029: copy_overflow (STB_LOCAL)
ffffffff819ad750-ffffffff819ad769: copy_overflow (STB_LOCAL)
ffffffff819b5b20-ffffffff819b5b39: copy_overflow (STB_LOCAL)
ffffffff819b6f70-ffffffff819b6f89: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/umip.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/sysctl.c (ffffffff8109f390)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/ptrace.c (ffffffff810a3542)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810a55cc)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810ad6c5)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/core.c (ffffffff810c3440)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8118a170)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811c1b50)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff811da670)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mempolicy.c (ffffffff8126fe9e)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (ffffffff812d98f0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/libfs.c (ffffffff812db990)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fd84e)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/binfmt_elf.c (ffffffff81318750)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff8131bea0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/iomap.c (ffffffff81323c80)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8133f720)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fat/dir.c (ffffffff813c02c0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff813d80a7)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/sem.c (ffffffff813f3940)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/keyctl.c (ffffffff81401650)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/dh.c (ffffffff81406e30)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/scsi_ioctl.c (ffffffff814be910)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (ffffffff814bf6d0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/pinctrl/pinconf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8156ee00)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff81630b00)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163eb30)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (ffffffff81666d24)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (ffffffff81667e40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff816f32a0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8170dc30)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/net/tun.c (ffffffff8175f290)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8178bf80)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm.c (ffffffff81832c80)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm-ioctl.c (ffffffff8183b060)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/socket.c (ffffffff8188f740)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (ffffffff81895400)
Location: include/linux/thread_info.h:132
Inline: True
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff818ac0f4)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffffffff818bb8b0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (ffffffff818d6160)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/compat.c (ffffffff818f51f3)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (ffffffff8190ba70)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191d4d2)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81923ac0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/raw.c (ffffffff819474b0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81949370)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b2440)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/udp.c (ffffffff819b90d0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819bd930)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d6dda)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff819e9598)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffffffff819ecde0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/wireless/wext-priv.c (ffffffff819ee230)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
**Symbols:**

```
ffffffff8109f390-ffffffff8109f3a9: copy_overflow (STB_LOCAL)
ffffffff810c3440-ffffffff810c3459: copy_overflow (STB_LOCAL)
ffffffff8118a170-ffffffff8118a189: copy_overflow (STB_LOCAL)
ffffffff811c1b50-ffffffff811c1b69: copy_overflow (STB_LOCAL)
ffffffff811da670-ffffffff811da689: copy_overflow (STB_LOCAL)
ffffffff812d98f0-ffffffff812d9909: copy_overflow (STB_LOCAL)
ffffffff812db990-ffffffff812db9a9: copy_overflow (STB_LOCAL)
ffffffff81318750-ffffffff81318769: copy_overflow (STB_LOCAL)
ffffffff8131bea0-ffffffff8131beb9: copy_overflow (STB_LOCAL)
ffffffff81323c80-ffffffff81323c99: copy_overflow (STB_LOCAL)
ffffffff8133f720-ffffffff8133f739: copy_overflow (STB_LOCAL)
ffffffff813c02c0-ffffffff813c02d9: copy_overflow (STB_LOCAL)
ffffffff813f3940-ffffffff813f3959: copy_overflow (STB_LOCAL)
ffffffff81401650-ffffffff81401669: copy_overflow (STB_LOCAL)
ffffffff81406e30-ffffffff81406e49: copy_overflow (STB_LOCAL)
ffffffff814be910-ffffffff814be929: copy_overflow (STB_LOCAL)
ffffffff814bf6d0-ffffffff814bf6e9: copy_overflow (STB_LOCAL)
ffffffff8156ee00-ffffffff8156ee19: copy_overflow (STB_LOCAL)
ffffffff81630b00-ffffffff81630b19: copy_overflow (STB_LOCAL)
ffffffff8163eb30-ffffffff8163eb49: copy_overflow (STB_LOCAL)
ffffffff81667e40-ffffffff81667e59: copy_overflow (STB_LOCAL)
ffffffff816f32a0-ffffffff816f32b9: copy_overflow (STB_LOCAL)
ffffffff8170dc30-ffffffff8170dc49: copy_overflow (STB_LOCAL)
ffffffff8175f290-ffffffff8175f2a9: copy_overflow (STB_LOCAL)
ffffffff8178bf80-ffffffff8178bf99: copy_overflow (STB_LOCAL)
ffffffff81832c80-ffffffff81832c99: copy_overflow (STB_LOCAL)
ffffffff8183b060-ffffffff8183b079: copy_overflow (STB_LOCAL)
ffffffff8188f740-ffffffff8188f759: copy_overflow (STB_LOCAL)
ffffffff81895400-ffffffff81895419: copy_overflow (STB_LOCAL)
ffffffff818bb8b0-ffffffff818bb8c9: copy_overflow (STB_LOCAL)
ffffffff818d6160-ffffffff818d6179: copy_overflow (STB_LOCAL)
ffffffff8190ba70-ffffffff8190ba89: copy_overflow (STB_LOCAL)
ffffffff81923ac0-ffffffff81923ad9: copy_overflow (STB_LOCAL)
ffffffff819474b0-ffffffff819474c9: copy_overflow (STB_LOCAL)
ffffffff81949370-ffffffff81949389: copy_overflow (STB_LOCAL)
ffffffff819b2440-ffffffff819b2459: copy_overflow (STB_LOCAL)
ffffffff819b90d0-ffffffff819b90e9: copy_overflow (STB_LOCAL)
ffffffff819bd930-ffffffff819bd949: copy_overflow (STB_LOCAL)
ffffffff819e40c0-ffffffff819e40d9: copy_overflow (STB_LOCAL)
ffffffff819ecde0-ffffffff819ecdf9: copy_overflow (STB_LOCAL)
ffffffff819ee230-ffffffff819ee249: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/umip.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/sysctl.c (ffffffff810a3aa0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/ptrace.c (ffffffff810a6ccb)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810aa2b0)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810b3022)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81197880)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d2220)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff811ef5e0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff811f7470)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mempolicy.c (ffffffff8128b4b7)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (ffffffff812f7e70)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/libfs.c (ffffffff812fa020)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/binfmt_elf.c (ffffffff813400a0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff81343780)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134cf70)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (ffffffff8135a480)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81367a10)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fat/dir.c (ffffffff813eaad0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff81402a35)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/sem.c (ffffffff8141fd90)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/keyctl.c (ffffffff8142e160)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/dh.c (ffffffff81433fd0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/scsi_ioctl.c (ffffffff814ed1c0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (ffffffff814edf20)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8159f310)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/keyboard.c (ffffffff81673080)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (ffffffff8169ca81)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (ffffffff8169d8c0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff8172c800)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff817493e0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/tun.c (ffffffff817a2870)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817ca350)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm.c (ffffffff81875270)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm-ioctl.c (ffffffff8187dd60)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/socket.c (ffffffff818d97a0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (ffffffff818e40c9)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/sysctl_net_core.c (ffffffff818f79ca)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffffffff819078a0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (ffffffff81923920)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (ffffffff8196d120)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197f836)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff819864e0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/raw.c (ffffffff819abb40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819ad9c0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a20a90)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/udp.c (ffffffff81a27be0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a2c410)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a45eba)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff81a57983)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffffffff81a5bfb0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/wireless/wext-priv.c (ffffffff81a5d480)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
**Symbols:**

```
ffffffff810a3aa0-ffffffff810a3ab9: copy_overflow (STB_LOCAL)
ffffffff81197880-ffffffff81197899: copy_overflow (STB_LOCAL)
ffffffff811d2220-ffffffff811d2239: copy_overflow (STB_LOCAL)
ffffffff811ef5e0-ffffffff811ef5f9: copy_overflow (STB_LOCAL)
ffffffff811f7470-ffffffff811f7489: copy_overflow (STB_LOCAL)
ffffffff812f7e70-ffffffff812f7e89: copy_overflow (STB_LOCAL)
ffffffff812fa020-ffffffff812fa039: copy_overflow (STB_LOCAL)
ffffffff813400a0-ffffffff813400b9: copy_overflow (STB_LOCAL)
ffffffff81343780-ffffffff81343799: copy_overflow (STB_LOCAL)
ffffffff8134cf70-ffffffff8134cf89: copy_overflow (STB_LOCAL)
ffffffff8135a480-ffffffff8135a499: copy_overflow (STB_LOCAL)
ffffffff81367a10-ffffffff81367a29: copy_overflow (STB_LOCAL)
ffffffff813eaad0-ffffffff813eaae9: copy_overflow (STB_LOCAL)
ffffffff8141fd90-ffffffff8141fda9: copy_overflow (STB_LOCAL)
ffffffff8142e160-ffffffff8142e179: copy_overflow (STB_LOCAL)
ffffffff81433fd0-ffffffff81433fe9: copy_overflow (STB_LOCAL)
ffffffff814ed1c0-ffffffff814ed1d9: copy_overflow (STB_LOCAL)
ffffffff814edf20-ffffffff814edf39: copy_overflow (STB_LOCAL)
ffffffff8159f310-ffffffff8159f329: copy_overflow (STB_LOCAL)
ffffffff81673080-ffffffff81673099: copy_overflow (STB_LOCAL)
ffffffff8169d8c0-ffffffff8169d8d9: copy_overflow (STB_LOCAL)
ffffffff8172c800-ffffffff8172c819: copy_overflow (STB_LOCAL)
ffffffff817493e0-ffffffff817493f9: copy_overflow (STB_LOCAL)
ffffffff8179cac0-ffffffff8179cad9: copy_overflow (STB_LOCAL)
ffffffff817ca350-ffffffff817ca369: copy_overflow (STB_LOCAL)
ffffffff81875270-ffffffff81875289: copy_overflow (STB_LOCAL)
ffffffff8187dd60-ffffffff8187dd79: copy_overflow (STB_LOCAL)
ffffffff818d97a0-ffffffff818d97b9: copy_overflow (STB_LOCAL)
ffffffff818dfa50-ffffffff818dfa69: copy_overflow (STB_LOCAL)
ffffffff819078a0-ffffffff819078b9: copy_overflow (STB_LOCAL)
ffffffff81923920-ffffffff81923939: copy_overflow (STB_LOCAL)
ffffffff8196d120-ffffffff8196d139: copy_overflow (STB_LOCAL)
ffffffff819864e0-ffffffff819864f9: copy_overflow (STB_LOCAL)
ffffffff819abb40-ffffffff819abb59: copy_overflow (STB_LOCAL)
ffffffff819ad9c0-ffffffff819ad9d9: copy_overflow (STB_LOCAL)
ffffffff81a20a90-ffffffff81a20aa9: copy_overflow (STB_LOCAL)
ffffffff81a27be0-ffffffff81a27bf9: copy_overflow (STB_LOCAL)
ffffffff81a2c410-ffffffff81a2c429: copy_overflow (STB_LOCAL)
ffffffff81a52fb0-ffffffff81a52fc9: copy_overflow (STB_LOCAL)
ffffffff81a5bfb0-ffffffff81a5bfc9: copy_overflow (STB_LOCAL)
ffffffff81a5d480-ffffffff81a5d499: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/umip.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/ptrace.c (ffffffff810ad5b6)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810b08af)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810b9612)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811de7c0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mempolicy.c (ffffffff8129b027)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (ffffffff81309a70)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/crypto/keyring.c (ffffffff8134cbe1)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8137fc90)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/dir.c (ffffffff81404b70)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff8141c7d2)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff81506600)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (ffffffff816bf7f1)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/tun.c (ffffffff817c4a00)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_igd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817faea0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (ffffffff81916c43)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff8192974a)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (ffffffff81955b50)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b5d76)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff819beae1)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a5e640)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7caaa)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff81a8cee3)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffffffff81a92be0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/wireless/wext-priv.c (ffffffff81a94090)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
**Symbols:**

```
ffffffff811de7c0-ffffffff811de7d9: copy_overflow (STB_LOCAL)
ffffffff81309a70-ffffffff81309a89: copy_overflow (STB_LOCAL)
ffffffff8137fc90-ffffffff8137fca9: copy_overflow (STB_LOCAL)
ffffffff81404b70-ffffffff81404b89: copy_overflow (STB_LOCAL)
ffffffff81506600-ffffffff81506619: copy_overflow (STB_LOCAL)
ffffffff817faea0-ffffffff817faeb9: copy_overflow (STB_LOCAL)
ffffffff81955b50-ffffffff81955b69: copy_overflow (STB_LOCAL)
ffffffff81a5e640-ffffffff81a5e659: copy_overflow (STB_LOCAL)
ffffffff81a89ba0-ffffffff81a89bb9: copy_overflow (STB_LOCAL)
ffffffff81a92be0-ffffffff81a92bf9: copy_overflow (STB_LOCAL)
ffffffff81a94090-ffffffff81a940a9: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/kernel/umip.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/ptrace.c (ffffffff810b4db4)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810b8aff)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810c0bce)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (ffffffff8111d290)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811ba900)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811fb8c0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8121fa40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/bpf/cgroup.c (ffffffff8122c0e0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (ffffffff813412a0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (ffffffff81342e40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/libfs.c (ffffffff813453a0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136af00)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/io_uring.c (ffffffff8137b660)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff8139ea50)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813a1b60)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (ffffffff813ba9c0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813ca140)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fat/dir.c (ffffffff81452d70)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff8146b512)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/sem.c (ffffffff81489da0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/keyctl.c (ffffffff814997c0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/dh.c (ffffffff8149fd60)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/scsi_ioctl.c (ffffffff81566f60)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (ffffffff81568560)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/iov_iter.c (ffffffff81586d50)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8166a3b0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/keyboard.c (ffffffff81748130)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (ffffffff81772ee1)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff8180f290)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81829a00)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8184ce70)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/tun.c (ffffffff8188a070)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189dbe0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a31f0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_igd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff818cae70)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/evdev.c (ffffffff8192f660)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm.c (ffffffff81976ea0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm-ioctl.c (ffffffff8197fe80)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/socket.c (ffffffff819dd970)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (ffffffff819e7482)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (ffffffff81a29650)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81a7e0f0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a7f5a0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9fa90)
Location: include/linux/thread_info.h:132
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81aa7b10)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad2150)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4f6b0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/udp.c (ffffffff81b57410)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b7748b)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff81b89f93)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffffffff81b8e0c0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/wireless/wext-priv.c (ffffffff81b8f640)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
**Symbols:**

```
ffffffff8111d290-ffffffff8111d2a9: copy_overflow (STB_LOCAL)
ffffffff811ba900-ffffffff811ba919: copy_overflow (STB_LOCAL)
ffffffff811fb8c0-ffffffff811fb8d9: copy_overflow (STB_LOCAL)
ffffffff8121fa40-ffffffff8121fa59: copy_overflow (STB_LOCAL)
ffffffff8122c0e0-ffffffff8122c0f9: copy_overflow (STB_LOCAL)
ffffffff813412a0-ffffffff813412b9: copy_overflow (STB_LOCAL)
ffffffff81342e40-ffffffff81342e59: copy_overflow (STB_LOCAL)
ffffffff813453a0-ffffffff813453b9: copy_overflow (STB_LOCAL)
ffffffff8136af00-ffffffff8136af19: copy_overflow (STB_LOCAL)
ffffffff8137b660-ffffffff8137b679: copy_overflow (STB_LOCAL)
ffffffff8139ea50-ffffffff8139ea69: copy_overflow (STB_LOCAL)
ffffffff813a1b60-ffffffff813a1b79: copy_overflow (STB_LOCAL)
ffffffff813ba9c0-ffffffff813ba9d9: copy_overflow (STB_LOCAL)
ffffffff813ca140-ffffffff813ca159: copy_overflow (STB_LOCAL)
ffffffff81452d70-ffffffff81452d89: copy_overflow (STB_LOCAL)
ffffffff8146b080-ffffffff8146b099: copy_overflow (STB_LOCAL)
ffffffff81489da0-ffffffff81489db9: copy_overflow (STB_LOCAL)
ffffffff814997c0-ffffffff814997d9: copy_overflow (STB_LOCAL)
ffffffff8149fd60-ffffffff8149fd79: copy_overflow (STB_LOCAL)
ffffffff81566f60-ffffffff81566f79: copy_overflow (STB_LOCAL)
ffffffff81568560-ffffffff81568579: copy_overflow (STB_LOCAL)
ffffffff81586d50-ffffffff81586d69: copy_overflow (STB_LOCAL)
ffffffff8166a3b0-ffffffff8166a3c9: copy_overflow (STB_LOCAL)
ffffffff81748130-ffffffff81748149: copy_overflow (STB_LOCAL)
ffffffff8180f290-ffffffff8180f2a9: copy_overflow (STB_LOCAL)
ffffffff81829a00-ffffffff81829a19: copy_overflow (STB_LOCAL)
ffffffff8184ce70-ffffffff8184ce89: copy_overflow (STB_LOCAL)
ffffffff8188a070-ffffffff8188a089: copy_overflow (STB_LOCAL)
ffffffff8189dbe0-ffffffff8189dbf9: copy_overflow (STB_LOCAL)
ffffffff818a31f0-ffffffff818a3209: copy_overflow (STB_LOCAL)
ffffffff818cae70-ffffffff818cae89: copy_overflow (STB_LOCAL)
ffffffff8192f660-ffffffff8192f679: copy_overflow (STB_LOCAL)
ffffffff81976ea0-ffffffff81976eb9: copy_overflow (STB_LOCAL)
ffffffff8197fe80-ffffffff8197fe99: copy_overflow (STB_LOCAL)
ffffffff819dd970-ffffffff819dd989: copy_overflow (STB_LOCAL)
ffffffff819e3ac0-ffffffff819e3ad9: copy_overflow (STB_LOCAL)
ffffffff81a29650-ffffffff81a29669: copy_overflow (STB_LOCAL)
ffffffff81a7e0f0-ffffffff81a7e109: copy_overflow (STB_LOCAL)
ffffffff81a7f5a0-ffffffff81a7f5b9: copy_overflow (STB_LOCAL)
ffffffff81a9fa90-ffffffff81a9faa9: copy_overflow (STB_LOCAL)
ffffffff81aa7b10-ffffffff81aa7b29: copy_overflow (STB_LOCAL)
ffffffff81ad2150-ffffffff81ad2169: copy_overflow (STB_LOCAL)
ffffffff81b4f6b0-ffffffff81b4f6c9: copy_overflow (STB_LOCAL)
ffffffff81b57410-ffffffff81b57429: copy_overflow (STB_LOCAL)
ffffffff81b85270-ffffffff81b85289: copy_overflow (STB_LOCAL)
ffffffff81b8e0c0-ffffffff81b8e0d9: copy_overflow (STB_LOCAL)
ffffffff81b8f640-ffffffff81b8f659: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/umip.c (ffffffff81081ef0)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/ptrace.c (ffffffff810aff94)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810b3daf)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810bbd3d)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/regset.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/printk/printk.c (ffffffff81117d60)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811b84d0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811fa930)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff812174e0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff812233f0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/bpf/cgroup.c (ffffffff812344d0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/seq_file.c (ffffffff8134d310)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/xattr.c (ffffffff8134f2f0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/libfs.c (ffffffff813516f0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81378460)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/io_uring.c (ffffffff81389900)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff813b0030)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813b2d20)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/proc/base.c (ffffffff813cc4f0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff813d8870)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/proc/kcore.c (ffffffff813dbe00)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/fat/dir.c (ffffffff8146f220)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff81485e22)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In ipc/sem.c (ffffffff814a73c0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In security/keys/keyctl.c (ffffffff814b7250)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In security/keys/dh.c (ffffffff814bd770)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In block/scsi_ioctl.c (ffffffff81581df0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In block/bsg.c (ffffffff81582ea0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In lib/iov_iter.c (ffffffff815a4020)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8168ad20)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/tty/tty_io.c (ffffffff81750bdb)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:iterate_tty_read
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/tty/vt/keyboard.c (ffffffff81763a80)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/char/random.c (ffffffff8178ded1)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/mfd/ab3100-core.c (ffffffff81819d95)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff8181e1d0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/dma-buf/dma-heap.c (ffffffff8183a3c0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8185d290)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/net/tun.c (ffffffff81898210)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ac870)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b1ea0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_igd.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff818d5f60)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/input/evdev.c (ffffffff81936970)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/md/dm.c (ffffffff8197bad0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/md/dm-ioctl.c (ffffffff81984270)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/socket.c (ffffffff819dd360)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/core/sock.c (ffffffff819e6fa8)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/core/filter.c (ffffffff81a28860)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a7f700)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/bpf/test_run.c (ffffffff81a87780)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a890c0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa98f0)
Location: include/linux/thread_info.h:197
Inline: True
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81ab2190)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ade290)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b65930)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b6a060)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7ea50)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b863f4)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff81b99ab3)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/wireless/wext-core.c (ffffffff81b9dd50)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/wireless/wext-priv.c (ffffffff81b9f280)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81bb5860)
Location: include/linux/thread_info.h:197
Inline: True
```
**Symbols:**

```
ffffffff81117d60-ffffffff81117d79: copy_overflow (STB_LOCAL)
ffffffff811b84d0-ffffffff811b84e9: copy_overflow (STB_LOCAL)
ffffffff811fa930-ffffffff811fa949: copy_overflow (STB_LOCAL)
ffffffff812174e0-ffffffff812174f9: copy_overflow (STB_LOCAL)
ffffffff812233f0-ffffffff81223409: copy_overflow (STB_LOCAL)
ffffffff812344d0-ffffffff812344e9: copy_overflow (STB_LOCAL)
ffffffff8134d310-ffffffff8134d329: copy_overflow (STB_LOCAL)
ffffffff8134f2f0-ffffffff8134f309: copy_overflow (STB_LOCAL)
ffffffff813516f0-ffffffff81351709: copy_overflow (STB_LOCAL)
ffffffff81378460-ffffffff81378479: copy_overflow (STB_LOCAL)
ffffffff81389900-ffffffff81389919: copy_overflow (STB_LOCAL)
ffffffff813b0030-ffffffff813b0049: copy_overflow (STB_LOCAL)
ffffffff813b2d20-ffffffff813b2d39: copy_overflow (STB_LOCAL)
ffffffff813cc4f0-ffffffff813cc509: copy_overflow (STB_LOCAL)
ffffffff813d8870-ffffffff813d8889: copy_overflow (STB_LOCAL)
ffffffff813dbe00-ffffffff813dbe19: copy_overflow (STB_LOCAL)
ffffffff8146f220-ffffffff8146f239: copy_overflow (STB_LOCAL)
ffffffff81485990-ffffffff814859a9: copy_overflow (STB_LOCAL)
ffffffff814a73c0-ffffffff814a73d9: copy_overflow (STB_LOCAL)
ffffffff814b7250-ffffffff814b7269: copy_overflow (STB_LOCAL)
ffffffff814bd770-ffffffff814bd789: copy_overflow (STB_LOCAL)
ffffffff81581df0-ffffffff81581e09: copy_overflow (STB_LOCAL)
ffffffff81582ea0-ffffffff81582eb9: copy_overflow (STB_LOCAL)
ffffffff815a4020-ffffffff815a4039: copy_overflow (STB_LOCAL)
ffffffff8168ad20-ffffffff8168ad39: copy_overflow (STB_LOCAL)
ffffffff81763a80-ffffffff81763a99: copy_overflow (STB_LOCAL)
ffffffff8181e1d0-ffffffff8181e1e9: copy_overflow (STB_LOCAL)
ffffffff8183a3c0-ffffffff8183a3d9: copy_overflow (STB_LOCAL)
ffffffff8185d290-ffffffff8185d2a9: copy_overflow (STB_LOCAL)
ffffffff81898210-ffffffff81898229: copy_overflow (STB_LOCAL)
ffffffff818ac870-ffffffff818ac889: copy_overflow (STB_LOCAL)
ffffffff818b1ea0-ffffffff818b1eb9: copy_overflow (STB_LOCAL)
ffffffff818d5f60-ffffffff818d5f79: copy_overflow (STB_LOCAL)
ffffffff81936970-ffffffff81936989: copy_overflow (STB_LOCAL)
ffffffff8197bad0-ffffffff8197bae9: copy_overflow (STB_LOCAL)
ffffffff81984270-ffffffff81984289: copy_overflow (STB_LOCAL)
ffffffff819dd360-ffffffff819dd379: copy_overflow (STB_LOCAL)
ffffffff819e3460-ffffffff819e3479: copy_overflow (STB_LOCAL)
ffffffff81a28860-ffffffff81a28879: copy_overflow (STB_LOCAL)
ffffffff81a7f700-ffffffff81a7f719: copy_overflow (STB_LOCAL)
ffffffff81a87780-ffffffff81a87799: copy_overflow (STB_LOCAL)
ffffffff81a890c0-ffffffff81a890d9: copy_overflow (STB_LOCAL)
ffffffff81aa98f0-ffffffff81aa9909: copy_overflow (STB_LOCAL)
ffffffff81ab2190-ffffffff81ab21a9: copy_overflow (STB_LOCAL)
ffffffff81ade290-ffffffff81ade2a9: copy_overflow (STB_LOCAL)
ffffffff81b65930-ffffffff81b65949: copy_overflow (STB_LOCAL)
ffffffff81b6a060-ffffffff81b6a079: copy_overflow (STB_LOCAL)
ffffffff81b7ea50-ffffffff81b7ea69: copy_overflow (STB_LOCAL)
ffffffff81b94bc0-ffffffff81b94bd9: copy_overflow (STB_LOCAL)
ffffffff81b9dd50-ffffffff81b9dd69: copy_overflow (STB_LOCAL)
ffffffff81b9f280-ffffffff81b9f299: copy_overflow (STB_LOCAL)
ffffffff81bb5860-ffffffff81bb5879: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/kernel/umip.c (ffffffff81082d10)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/ptrace.c (ffffffff810b1525)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810b533b)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810bd5dd)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/regset.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/printk/printk.c (ffffffff81118430)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811b8400)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811fb880)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff8121a950)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff81227ea0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/bpf/cgroup.c (ffffffff81238310)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/events/core.c (ffffffff8123ee00)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In mm/mempolicy.c (ffffffff812e0b2c)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/seq_file.c (ffffffff81353f10)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/xattr.c (ffffffff81355de0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/libfs.c (ffffffff81358410)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137f080)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/io_uring.c (ffffffff81390740)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff813b7160)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813b9e00)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/proc/base.c (ffffffff813d34b0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff813df740)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/proc/kcore.c (ffffffff813e2da0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/fat/dir.c (ffffffff814746e0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff8148b879)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In ipc/sem.c (ffffffff814ad2f0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In security/keys/keyctl.c (ffffffff814bd0b0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In security/keys/dh.c (ffffffff814c35e0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In block/scsi_ioctl.c (ffffffff81588bf0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In block/bsg.c (ffffffff81589cd0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8166da10)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/tty/tty_io.c (ffffffff81734ad7)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/tty/vt/keyboard.c (ffffffff81747630)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/char/random.c (ffffffff81770881)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/char/virtio_console.c (ffffffff817720b0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff81801520)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/dma-buf/dma-heap.c (ffffffff8181d5e0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff818400a0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/net/tun.c (ffffffff8187aae0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188f9b0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818952d0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_igd.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff818b94a0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/input/evdev.c (ffffffff8191a1f0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/md/dm.c (ffffffff8195fcd0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/md/dm-ioctl.c (ffffffff819685f0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/platform/x86/intel_pmc_core.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/socket.c (ffffffff819c35b0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/core/sock.c (ffffffff819cd0ff)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/core/filter.c (ffffffff81a0fc40)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a686d0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/bpf/test_run.c (ffffffff81a70850)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a72750)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a94ac0)
Location: include/linux/thread_info.h:197
Inline: True
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81a9d420)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81ac6bd0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ac92b0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b53be0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b58350)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d650)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b750a4)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff81b87fa1)
Location: include/linux/thread_info.h:197
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/wireless/wext-core.c (ffffffff81b8ce50)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/wireless/wext-priv.c (ffffffff81b8e360)
Location: include/linux/thread_info.h:197
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba4840)
Location: include/linux/thread_info.h:197
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/thread_info.h:197
Inline: True
```
**Symbols:**

```
ffffffff81118430-ffffffff81118449: copy_overflow (STB_LOCAL)
ffffffff811b8400-ffffffff811b8419: copy_overflow (STB_LOCAL)
ffffffff811fb880-ffffffff811fb899: copy_overflow (STB_LOCAL)
ffffffff8121a950-ffffffff8121a969: copy_overflow (STB_LOCAL)
ffffffff81227ea0-ffffffff81227eb9: copy_overflow (STB_LOCAL)
ffffffff81238310-ffffffff81238329: copy_overflow (STB_LOCAL)
ffffffff8123ee00-ffffffff8123ee19: copy_overflow (STB_LOCAL)
ffffffff81353f10-ffffffff81353f29: copy_overflow (STB_LOCAL)
ffffffff81355de0-ffffffff81355df9: copy_overflow (STB_LOCAL)
ffffffff81358410-ffffffff81358429: copy_overflow (STB_LOCAL)
ffffffff8137f080-ffffffff8137f099: copy_overflow (STB_LOCAL)
ffffffff81390740-ffffffff81390759: copy_overflow (STB_LOCAL)
ffffffff813b7160-ffffffff813b7179: copy_overflow (STB_LOCAL)
ffffffff813b9e00-ffffffff813b9e19: copy_overflow (STB_LOCAL)
ffffffff813d34b0-ffffffff813d34c9: copy_overflow (STB_LOCAL)
ffffffff813df740-ffffffff813df759: copy_overflow (STB_LOCAL)
ffffffff813e2da0-ffffffff813e2db9: copy_overflow (STB_LOCAL)
ffffffff814746e0-ffffffff814746f9: copy_overflow (STB_LOCAL)
ffffffff8148b400-ffffffff8148b419: copy_overflow (STB_LOCAL)
ffffffff814ad2f0-ffffffff814ad309: copy_overflow (STB_LOCAL)
ffffffff814bd0b0-ffffffff814bd0c9: copy_overflow (STB_LOCAL)
ffffffff814c35e0-ffffffff814c35f9: copy_overflow (STB_LOCAL)
ffffffff81588bf0-ffffffff81588c09: copy_overflow (STB_LOCAL)
ffffffff81589cd0-ffffffff81589ce9: copy_overflow (STB_LOCAL)
ffffffff8166da10-ffffffff8166da29: copy_overflow (STB_LOCAL)
ffffffff81747630-ffffffff81747649: copy_overflow (STB_LOCAL)
ffffffff817720b0-ffffffff817720c9: copy_overflow (STB_LOCAL)
ffffffff81801520-ffffffff81801539: copy_overflow (STB_LOCAL)
ffffffff8181d5e0-ffffffff8181d5f9: copy_overflow (STB_LOCAL)
ffffffff818400a0-ffffffff818400b9: copy_overflow (STB_LOCAL)
ffffffff8187aae0-ffffffff8187aaf9: copy_overflow (STB_LOCAL)
ffffffff8188f9b0-ffffffff8188f9c9: copy_overflow (STB_LOCAL)
ffffffff818952d0-ffffffff818952e9: copy_overflow (STB_LOCAL)
ffffffff818b94a0-ffffffff818b94b9: copy_overflow (STB_LOCAL)
ffffffff8191a1f0-ffffffff8191a209: copy_overflow (STB_LOCAL)
ffffffff8195fcd0-ffffffff8195fce9: copy_overflow (STB_LOCAL)
ffffffff819685f0-ffffffff81968609: copy_overflow (STB_LOCAL)
ffffffff819c35b0-ffffffff819c35c9: copy_overflow (STB_LOCAL)
ffffffff819c94e0-ffffffff819c94f9: copy_overflow (STB_LOCAL)
ffffffff81a0fc40-ffffffff81a0fc59: copy_overflow (STB_LOCAL)
ffffffff81a686d0-ffffffff81a686e9: copy_overflow (STB_LOCAL)
ffffffff81a70850-ffffffff81a70869: copy_overflow (STB_LOCAL)
ffffffff81a72750-ffffffff81a72769: copy_overflow (STB_LOCAL)
ffffffff81a94ac0-ffffffff81a94ad9: copy_overflow (STB_LOCAL)
ffffffff81a9d420-ffffffff81a9d439: copy_overflow (STB_LOCAL)
ffffffff81ac6bd0-ffffffff81ac6be9: copy_overflow (STB_LOCAL)
ffffffff81ac92b0-ffffffff81ac92c9: copy_overflow (STB_LOCAL)
ffffffff81b53be0-ffffffff81b53bf9: copy_overflow (STB_LOCAL)
ffffffff81b58350-ffffffff81b58369: copy_overflow (STB_LOCAL)
ffffffff81b6d650-ffffffff81b6d669: copy_overflow (STB_LOCAL)
ffffffff81b83ca0-ffffffff81b83cb9: copy_overflow (STB_LOCAL)
ffffffff81b8ce50-ffffffff81b8ce69: copy_overflow (STB_LOCAL)
ffffffff81b8e360-ffffffff81b8e379: copy_overflow (STB_LOCAL)
ffffffff81ba4840-ffffffff81ba4859: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff81091dc5)
Location: include/linux/thread_info.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/capability.c (ffffffff810c2ab0)
Location: include/linux/thread_info.h:198
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/ptrace.c (ffffffff810c3805)
Location: include/linux/thread_info.h:198
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810c791b)
Location: include/linux/thread_info.h:198
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810cfc7d)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/regset.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff8122ce80)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff81251750)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In mm/mempolicy.c (ffffffff81327e94)
Location: include/linux/thread_info.h:198
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/fat/dir.c (ffffffff814cb420)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff814e2f19)
Location: include/linux/thread_info.h:198
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In drivers/tty/tty_io.c (ffffffff817b5437)
Location: include/linux/thread_info.h:198
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/char/random.c (ffffffff817f6296)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/dma-buf/dma-heap.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff818cf5f8)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_igd.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8194ef80)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/core/sock.c (ffffffff81a7d159)
Location: include/linux/thread_info.h:198
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51766)
Location: include/linux/thread_info.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81b5f23f)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/thread_info.h:198
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81c3f9c6)
Location: include/linux/thread_info.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff81c506d0)
Location: include/linux/thread_info.h:198
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/thread_info.h:198
Inline: True
```
**Symbols:**

```
ffffffff8122ce80-ffffffff8122ce99: copy_overflow (STB_LOCAL)
ffffffff81251750-ffffffff81251769: copy_overflow (STB_LOCAL)
ffffffff814cb420-ffffffff814cb439: copy_overflow (STB_LOCAL)
ffffffff8194ef80-ffffffff8194ef99: copy_overflow (STB_LOCAL)
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
In arch/x86/coco/tdx/tdx.c (ffffffff81003110)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_get_report
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff810a2fd5)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/capability.c (ffffffff810d9fab)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/ptrace.c (ffffffff810daf8a)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810de5fd)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810e821a)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - kernel/sys.c:override_release
```
```
In kernel/regset.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/printk/printk.c (ffffffff8115c5eb)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
```
```
In kernel/module/main.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/mempolicy.c (ffffffff81397066)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff815713e2)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/pci/vgaarb.c (ffffffff817f378c)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_read
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/tty/tty_io.c (ffffffff818f135d)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81908d38)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/dma-buf/dma-heap.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81a1d2d8)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_igd.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/core/sock.c (ffffffff81bf3357)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81cb6b32)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
```
In net/ethtool/ioctl.c (ffffffff81cb9cee)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cde624)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81cedc8a)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/mptcp/sockopt.c (ffffffff81e33a9f)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/thread_info.h:214
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
In arch/x86/kernel/signal_64.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In arch/x86/kernel/signal_32.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff810bb2a5)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/capability.c (ffffffff810f9f5b)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/ptrace.c (ffffffff810fb0bf)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810feb4d)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff81108f9a)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - kernel/sys.c:override_release
```
```
In kernel/regset.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/printk/printk.c (ffffffff8118f0cb)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
```
```
In kernel/module/main.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff816166a8)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/apparmor/notify.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In io_uring/filetable.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In io_uring/openclose.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In io_uring/epoll.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In io_uring/net.c (ffffffff81796ea9)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg
```
```
In io_uring/tctx.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In io_uring/cancel.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In io_uring/kbuf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/pci/vgaarb.c (ffffffff8191dd5c)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_read
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/tty/tty_io.c (ffffffff81a4a53d)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a63336)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/dma-buf/dma-heap.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81b9e5a8)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/core/sock.c (ffffffff81da0ff2)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81e75092)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
```
In net/ethtool/ioctl.c (ffffffff81e78251)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea214b)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81eb4bca)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f2224f)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/thread_info.h:214
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f82312)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/udp.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81fb0194)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In net/mptcp/sockopt.c (ffffffff8200bbbf)
Location: include/linux/thread_info.h:214
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:214
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/thread_info.h:214
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
In arch/x86/kernel/signal_64.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In arch/x86/kernel/signal_32.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff810be3e2)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/capability.c (ffffffff8110621c)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/ptrace.c (ffffffff81106ff3)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff8110abbc)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff811152aa)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - kernel/sys.c:override_release
```
```
In kernel/regset.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/printk/printk.c (ffffffff811a096b)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/log.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff8164e728)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/apparmor/notify.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In crypto/jitterentropy-testing.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/filetable.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/openclose.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/epoll.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/net.c (ffffffff817d7cef)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg
```
```
In io_uring/tctx.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/cancel.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/kbuf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/pci/vgaarb.c (ffffffff8196130c)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_read
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/video/fbdev/core/fb_io_fops.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/video/fbdev/core/fb_sys_fops.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/tty/tty_io.c (ffffffff81a94759)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aada01)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/dma-buf/dma-heap.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81bf4bc5)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/core/sock.c (ffffffff81e0f920)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81ed1201)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
```
In net/ethtool/ioctl.c (ffffffff81ed4631)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81f00961)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81f12f8d)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f81dfc)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe265e)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/udp.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820108f5)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff8202bea2)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/mptcp/sockopt.c (ffffffff82088e12)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/thread_info.h:230
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
In arch/x86/kernel/signal_64.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In arch/x86/kernel/signal_32.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff810c5562)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/capability.c (ffffffff8110fb6c)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/ptrace.c (ffffffff81110943)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff8111455c)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff8111ec9a)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - kernel/sys.c:override_release
```
```
In kernel/regset.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/printk/printk.c (ffffffff811afa5a)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/module/main.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/log.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/bpf_iter.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/mprog.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/bpf/net_namespace.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In kernel/watch_queue.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff81687c88)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/debugfs/file.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/security.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/apparmor/notify.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In security/landlock/syscalls.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/filetable.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/openclose.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/epoll.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/net.c (ffffffff8181bfaa)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg
```
```
In io_uring/tctx.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/cancel.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/kbuf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In io_uring/register.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8195039e)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
```
```
In drivers/pci/vgaarb.c (ffffffff819aaa8b)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_read
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/video/fbdev/core/fb_chrdev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/video/fbdev/core/fb_io_fops.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/video/fbdev/core/fb_sys_fops.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/tty/tty_io.c (ffffffff81ae7310)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81b00621)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/iommu/intel/nested.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/dma-buf/dma-heap.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81c4a505)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpu/drm/drm_color_mgmt.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpu/drm/drm_connector.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpu/drm/drm_file.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpu/drm/drm_framebuffer.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpu/drm/drm_gem.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpu/drm/drm_ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpu/drm/drm_plane.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpu/drm/drm_property.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpu/drm/drm_syncobj.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/gpu/drm/drm_ioc32.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/gpu/drm/drm_debugfs.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/gpu/drm/drm_debugfs_crc.c (ffffffff81cbb736)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/net/phy/phy.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/core/sock.c (ffffffff81ecc458)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81f94ca8)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
```
In net/ethtool/ioctl.c (ffffffff81f98070)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc4c02)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81fd7337)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8204847c)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
```
```
In net/ipv4/tcp_ao.c (ffffffff82059adc)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_get_repair
  - net/ipv4/tcp_ao.c:tcp_ao_get_sock_info
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/thread_info.h:230
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820b057c)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/udp.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820df885)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff820fb953)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In net/mptcp/sockopt.c (ffffffff8215e892)
Location: include/linux/thread_info.h:230
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/thread_info.h:230
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/arm64/kernel/signal32.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/arm64/kernel/crash_dump.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In virt/kvm/kvm_main.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In virt/kvm/arm/arm.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In virt/kvm/arm/psci.c (ffff8000100cefd8)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - virt/kvm/arm/psci.c:kvm_arm_set_fw_reg
  - virt/kvm/arm/psci.c:kvm_arm_get_fw_reg
```
```
In arch/arm64/kvm/guest.c (ffff8000100d3390)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
```
```
In arch/arm64/kvm/sys_regs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-kvm-device.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In virt/kvm/arm/vgic/vgic-its.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/ptrace.c (ffff800010107984)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffff80001010c0c8)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffff800010116b0c)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_newuname
```
```
In kernel/sched/core.c (ffff800010132b48)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (ffff80001021e468)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (ffff80001025fb40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (ffff800010282228)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/cgroup.c (ffff80001028cc40)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/events/core.c (ffff8000102913e8)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mempolicy.c (ffff800010339c1c)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (ffff8000103bdc88)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/libfs.c (ffff8000103c02c0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/crypto/keyring.c (ffff80001040d9f0)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/binfmt_elf.c (ffff80001041dcc0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/iomap/direct-io.c (ffff80001042c720)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (ffff80001043cbd8)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/kcore.c (ffff80001044d630)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fat/dir.c (ffff8000104e3868)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fd910)
Location: include/linux/thread_info.h:132
Inline: False
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/sem.c (ffff800010521568)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/keyctl.c (ffff800010531880)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/dh.c (ffff800010537ec0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/scsi_ioctl.c (ffff800010607930)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (ffff800010748ba0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/keyboard.c (ffff800010869d80)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (ffff8000108b0d10)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/nvdimm/bus.c (ffff800010950978)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (ffff80001096fca0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/tun.c (ffff8000109dac40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (ffff800010a2bf38)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm.c (ffff800010afc320)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm-ioctl.c (ffff800010b06ac8)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mmc/core/block.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/socket.c (ffff800010ba0cb8)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (ffff800010ba96d8)
Location: include/linux/thread_info.h:132
Inline: True
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/sysctl_net_core.c (ffff800010bc5d64)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffff800010bd8c10)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (ffff800010bf79a0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (ffff800010c527f8)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffff800010c6715c)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffff800010c6eee8)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/raw.c (ffff800010c96698)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1c320)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/udp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d472bc)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffff800010d5d5d0)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffff800010d60998)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/wireless/wext-priv.c (ffff800010d624a0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
**Symbols:**

```
ffff8000100d19d8-ffff8000100d1a00: copy_overflow (STB_LOCAL)
ffff800010132b48-ffff800010132b70: copy_overflow (STB_LOCAL)
ffff80001021e468-ffff80001021e490: copy_overflow (STB_LOCAL)
ffff80001025fb40-ffff80001025fb68: copy_overflow (STB_LOCAL)
ffff800010282228-ffff800010282250: copy_overflow (STB_LOCAL)
ffff80001028cc40-ffff80001028cc68: copy_overflow (STB_LOCAL)
ffff8000102913e8-ffff800010291410: copy_overflow (STB_LOCAL)
ffff8000103bdc88-ffff8000103bdcb0: copy_overflow (STB_LOCAL)
ffff8000103c02c0-ffff8000103c02e8: copy_overflow (STB_LOCAL)
ffff80001041dcc0-ffff80001041dce8: copy_overflow (STB_LOCAL)
ffff80001042c720-ffff80001042c748: copy_overflow (STB_LOCAL)
ffff80001043cbd8-ffff80001043cc00: copy_overflow (STB_LOCAL)
ffff80001044d630-ffff80001044d658: copy_overflow (STB_LOCAL)
ffff8000104e3868-ffff8000104e3890: copy_overflow (STB_LOCAL)
ffff8000104fd910-ffff8000104fd938: copy_overflow (STB_LOCAL)
ffff800010521568-ffff800010521590: copy_overflow (STB_LOCAL)
ffff800010531880-ffff8000105318a8: copy_overflow (STB_LOCAL)
ffff800010537ec0-ffff800010537ee8: copy_overflow (STB_LOCAL)
ffff800010607930-ffff800010607958: copy_overflow (STB_LOCAL)
ffff800010748ba0-ffff800010748bc8: copy_overflow (STB_LOCAL)
ffff800010869d80-ffff800010869da8: copy_overflow (STB_LOCAL)
ffff800010950978-ffff8000109509a0: copy_overflow (STB_LOCAL)
ffff80001096fca0-ffff80001096fcc8: copy_overflow (STB_LOCAL)
ffff8000109dac40-ffff8000109dac68: copy_overflow (STB_LOCAL)
ffff800010a2bf38-ffff800010a2bf60: copy_overflow (STB_LOCAL)
ffff800010afc320-ffff800010afc348: copy_overflow (STB_LOCAL)
ffff800010b06ac8-ffff800010b06af0: copy_overflow (STB_LOCAL)
ffff800010ba0cb8-ffff800010ba0ce0: copy_overflow (STB_LOCAL)
ffff800010ba96d8-ffff800010ba9700: copy_overflow (STB_LOCAL)
ffff800010bd8c10-ffff800010bd8c38: copy_overflow (STB_LOCAL)
ffff800010bf79a0-ffff800010bf79c8: copy_overflow (STB_LOCAL)
ffff800010c527f8-ffff800010c52820: copy_overflow (STB_LOCAL)
ffff800010c6eee8-ffff800010c6ef10: copy_overflow (STB_LOCAL)
ffff800010c96698-ffff800010c966c0: copy_overflow (STB_LOCAL)
ffff800010d1c320-ffff800010d1c348: copy_overflow (STB_LOCAL)
ffff800010d569b8-ffff800010d569e0: copy_overflow (STB_LOCAL)
ffff800010d60998-ffff800010d609c0: copy_overflow (STB_LOCAL)
ffff800010d624a0-ffff800010d624c8: copy_overflow (STB_LOCAL)
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
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/arm/kernel/crash_dump.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/ptrace.c (c036222c)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sys.c (c036b1c0)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_newuname
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/crypto/keyring.c (c05da780)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/binfmt_elf_fdpic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/binfmt_flat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/dir.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ecryptfs/miscdev.c (c06bb710)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (c09aa54c)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/mtd/mtdchar.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/ethernet/ti/cpsw.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/usb/musb/musb_debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/rtc/rtc-pcf8523.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/firmware/tegra/bpmp-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In sound/core/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In sound/core/control.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In sound/core/info.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In sound/core/timer.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In sound/core/pcm_native.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In sound/core/pcm_lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In sound/core/compress_offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In sound/soc/soc-generic-dmaengine-pcm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (c0ccd6a8)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sysctl_net_core.c (c0ce0f98)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (c0d76618)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp.c (c0d80eec)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e49340)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/powerpc/kernel/signal_32.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/powerpc/kernel/rtas.c (c00000000003f2f0)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:__se_sys_rtas
```
```
In arch/powerpc/kernel/rtasd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/powerpc/kernel/rtas-proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/powerpc/kernel/crash_dump.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/powerpc/mm/numa.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/powerpc/lib/checksum_wrappers.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/powerpc/platforms/pseries/lpar.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/powerpc/platforms/pseries/dtl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/powerpc/platforms/pseries/lparcfg.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/sysctl.c (c000000000149a40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/ptrace.c (c00000000014e278)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (c000000000152f20)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/signal.c:__se_compat_sys_rt_sigpending
```
```
In kernel/sys.c (c00000000015d6e8)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (c0000000001caee0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (c0000000002a15e0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (c000000000304b40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/cgroup.c (c000000000339220)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mempolicy.c (c000000000414420)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (c0000000004bbca0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/libfs.c (c0000000004bf830)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/crypto/keyring.c (c00000000051ad20)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/binfmt_elf.c (c00000000052c5a0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/compat_binfmt_elf.c (c000000000530260)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fhandle.c (c000000000539590)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/iomap/direct-io.c (c00000000053d3c0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (c0000000005508e0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/kcore.c (c000000000564fd0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fat/dir.c (c000000000620d40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ecryptfs/miscdev.c (c0000000006410d0)
Location: include/linux/thread_info.h:132
Inline: False
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/sem.c (c00000000066a920)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/keyctl.c (c00000000067efb0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/dh.c (c000000000687060)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/scsi_ioctl.c (c0000000007a4650)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (c0000000007a5cd0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/iov_iter.c (c0000000007d0aa0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (c0000000008a9ed0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/keyboard.c (c000000000909fa0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (c00000000094847c)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (c00000000094b630)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/nvram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/nvdimm/bus.c (c0000000009fd440)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (c000000000a29360)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/tun.c (c000000000aa4b20)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/vfio_iommu_spapr_tce.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/vfio_spapr_eeh.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab5060)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_nvlink2.c (c000000000abe230)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (c000000000ae9850)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm.c (c000000000bea6e0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm-ioctl.c (c000000000bf79f0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/socket.c (c000000000c74c40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (c000000000c7eb40)
Location: include/linux/thread_info.h:132
Inline: True
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/sysctl_net_core.c (c000000000ca0930)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (c000000000cb86e0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (c000000000cdd860)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (c000000000d520c0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (c000000000d6b470)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (c000000000d75140)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (c000000000daaae0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/udp.c (c000000000e53620)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e7ca3c)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (c000000000e96374)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (c000000000e9bba0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/wireless/wext-priv.c (c000000000e9dac0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
**Symbols:**

```
c000000000149a40-c000000000149a84: copy_overflow (STB_LOCAL)
c0000000001caee0-c0000000001caf24: copy_overflow (STB_LOCAL)
c0000000002a15e0-c0000000002a1624: copy_overflow (STB_LOCAL)
c000000000304b40-c000000000304b84: copy_overflow (STB_LOCAL)
c000000000339220-c000000000339264: copy_overflow (STB_LOCAL)
c0000000004bbca0-c0000000004bbce4: copy_overflow (STB_LOCAL)
c0000000004bf830-c0000000004bf874: copy_overflow (STB_LOCAL)
c00000000052c5a0-c00000000052c5e4: copy_overflow (STB_LOCAL)
c000000000530260-c0000000005302a4: copy_overflow (STB_LOCAL)
c000000000539590-c0000000005395d4: copy_overflow (STB_LOCAL)
c00000000053d3c0-c00000000053d404: copy_overflow (STB_LOCAL)
c0000000005508e0-c000000000550924: copy_overflow (STB_LOCAL)
c000000000564fd0-c000000000565014: copy_overflow (STB_LOCAL)
c000000000620d40-c000000000620d84: copy_overflow (STB_LOCAL)
c0000000006410d0-c000000000641114: copy_overflow (STB_LOCAL)
c00000000066a920-c00000000066a964: copy_overflow (STB_LOCAL)
c00000000067efb0-c00000000067eff4: copy_overflow (STB_LOCAL)
c000000000687060-c0000000006870a4: copy_overflow (STB_LOCAL)
c0000000007a4650-c0000000007a4694: copy_overflow (STB_LOCAL)
c0000000007a5cd0-c0000000007a5d14: copy_overflow (STB_LOCAL)
c0000000007d0aa0-c0000000007d0ae4: copy_overflow (STB_LOCAL)
c0000000008a9ed0-c0000000008a9f14: copy_overflow (STB_LOCAL)
c000000000909fa0-c000000000909fe4: copy_overflow (STB_LOCAL)
c00000000094b630-c00000000094b674: copy_overflow (STB_LOCAL)
c0000000009fd440-c0000000009fd484: copy_overflow (STB_LOCAL)
c000000000a29360-c000000000a293a4: copy_overflow (STB_LOCAL)
c000000000a9cd60-c000000000a9cda4: copy_overflow (STB_LOCAL)
c000000000ab5060-c000000000ab50a4: copy_overflow (STB_LOCAL)
c000000000abe230-c000000000abe274: copy_overflow (STB_LOCAL)
c000000000ae9850-c000000000ae9894: copy_overflow (STB_LOCAL)
c000000000bea6e0-c000000000bea724: copy_overflow (STB_LOCAL)
c000000000bf79f0-c000000000bf7a34: copy_overflow (STB_LOCAL)
c000000000c74c40-c000000000c74c84: copy_overflow (STB_LOCAL)
c000000000c7eb40-c000000000c7eb84: copy_overflow (STB_LOCAL)
c000000000cb86e0-c000000000cb8724: copy_overflow (STB_LOCAL)
c000000000cdd860-c000000000cdd8a4: copy_overflow (STB_LOCAL)
c000000000d520c0-c000000000d52104: copy_overflow (STB_LOCAL)
c000000000d75140-c000000000d75184: copy_overflow (STB_LOCAL)
c000000000daaae0-c000000000daab24: copy_overflow (STB_LOCAL)
c000000000e53620-c000000000e53664: copy_overflow (STB_LOCAL)
c000000000e8fec0-c000000000e8ff04: copy_overflow (STB_LOCAL)
c000000000e9bba0-c000000000e9bbe4: copy_overflow (STB_LOCAL)
c000000000e9dac0-c000000000e9db04: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/ptrace.c (ffffffe0000cb966)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/sys.c (ffffffe0000d2770)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_newuname
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (ffffffe00010e326)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (ffffffe00017af36)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffe00019d9f0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (ffffffe0001b835c)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffe0001c0304)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (ffffffe00027ee50)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/libfs.c (ffffffe000280ae6)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/crypto/keyring.c (ffffffe0002b6d66)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/binfmt_elf.c (ffffffe0002c0584)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/binfmt_flat.c (ffffffe0002c288a)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fhandle.c (ffffffe0002c724c)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffe0002c960c)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (ffffffe0002d4e20)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/kcore.c (ffffffe0002e2204)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/fat/dir.c (ffffffe00035707a)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffe00036c5c8)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/sem.c (ffffffe00038772a)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/keys/keyctl.c (ffffffe000392740)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/dh.c (ffffffe000397032)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/scsi_ioctl.c (ffffffe00044243a)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (ffffffe000443070)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffe0004f741c)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/keyboard.c (ffffffe00053ebb8)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (ffffffe0005622e2)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (ffffffe000564b92)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffe0005c0ac8)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_ioctl.c (ffffffe0005d9bca)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/tun.c (ffffffe000625a46)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffe00064dbc6)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (ffffffe0006ad04a)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm.c (ffffffe0006ed5ac)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f5732)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mmc/core/block.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/socket.c (ffffffe000738a5c)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (ffffffe00073c7fe)
Location: include/linux/thread_info.h:132
Inline: True
Direct callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/sysctl_net_core.c (ffffffe0007521b2)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffffffe000761872)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (ffffffe000779166)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (ffffffe0007bd790)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cd71e)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d3c80)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/raw.c (ffffffe0007f5870)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007f6e9e)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe00085ff74)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/udp.c (ffffffe000864eae)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (ffffffe0008699e4)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe0008816c8)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffe00088e318)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/wireless/wext-core.c (ffffffe000895d8c)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/wireless/wext-priv.c (ffffffe000896eae)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
**Symbols:**

```
ffffffe00010e326-ffffffe00010e34c: copy_overflow (STB_LOCAL)
ffffffe00017af36-ffffffe00017af5c: copy_overflow (STB_LOCAL)
ffffffe0002c0584-ffffffe0002c05aa: copy_overflow (STB_LOCAL)
ffffffe0002c288a-ffffffe0002c28b0: copy_overflow (STB_LOCAL)
ffffffe0002d4e20-ffffffe0002d4e46: copy_overflow (STB_LOCAL)
ffffffe0002e2204-ffffffe0002e222a: copy_overflow (STB_LOCAL)
ffffffe00038772a-ffffffe000387750: copy_overflow (STB_LOCAL)
ffffffe00044243a-ffffffe000442460: copy_overflow (STB_LOCAL)
ffffffe000443070-ffffffe000443096: copy_overflow (STB_LOCAL)
ffffffe00053ebb8-ffffffe00053ebde: copy_overflow (STB_LOCAL)
ffffffe000564b92-ffffffe000564bb8: copy_overflow (STB_LOCAL)
ffffffe0005c0ac8-ffffffe0005c0aee: copy_overflow (STB_LOCAL)
ffffffe000625a46-ffffffe000625a6c: copy_overflow (STB_LOCAL)
ffffffe00064dbc6-ffffffe00064dbec: copy_overflow (STB_LOCAL)
ffffffe0006ed5ac-ffffffe0006ed5d2: copy_overflow (STB_LOCAL)
ffffffe0006f5732-ffffffe0006f5758: copy_overflow (STB_LOCAL)
ffffffe000738a5c-ffffffe000738a82: copy_overflow (STB_LOCAL)
ffffffe00073c7fe-ffffffe00073c824: copy_overflow (STB_LOCAL)
ffffffe0007bd790-ffffffe0007bd7b6: copy_overflow (STB_LOCAL)
ffffffe0007d3c80-ffffffe0007d3ca6: copy_overflow (STB_LOCAL)
ffffffe0007f5870-ffffffe0007f5896: copy_overflow (STB_LOCAL)
ffffffe0007f6e9e-ffffffe0007f6ec4: copy_overflow (STB_LOCAL)
ffffffe000864eae-ffffffe000864ed4: copy_overflow (STB_LOCAL)
ffffffe0008699e4-ffffffe000869a0a: copy_overflow (STB_LOCAL)
ffffffe00088e318-ffffffe00088e33e: copy_overflow (STB_LOCAL)
ffffffe000895d8c-ffffffe000895db2: copy_overflow (STB_LOCAL)
ffffffe00019d9f0-ffffffe00019da16: copy_overflow (STB_LOCAL)
ffffffe0001b835c-ffffffe0001b8382: copy_overflow (STB_LOCAL)
ffffffe0001c0304-ffffffe0001c032a: copy_overflow (STB_LOCAL)
ffffffe00027ee50-ffffffe00027ee76: copy_overflow (STB_LOCAL)
ffffffe000280ae6-ffffffe000280b0c: copy_overflow (STB_LOCAL)
ffffffe0002c724c-ffffffe0002c7272: copy_overflow (STB_LOCAL)
ffffffe0002c960c-ffffffe0002c9632: copy_overflow (STB_LOCAL)
ffffffe00035707a-ffffffe0003570a0: copy_overflow (STB_LOCAL)
ffffffe000392740-ffffffe000392766: copy_overflow (STB_LOCAL)
ffffffe000397032-ffffffe000397058: copy_overflow (STB_LOCAL)
ffffffe0004f741c-ffffffe0004f7442: copy_overflow (STB_LOCAL)
ffffffe0005d9bca-ffffffe0005d9bf0: copy_overflow (STB_LOCAL)
ffffffe000761872-ffffffe000761898: copy_overflow (STB_LOCAL)
ffffffe000779166-ffffffe00077918c: copy_overflow (STB_LOCAL)
ffffffe00085ff74-ffffffe00085ff9a: copy_overflow (STB_LOCAL)
ffffffe000896eae-ffffffe000896ed4: copy_overflow (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/umip.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/ptrace.c (ffffffff810a7926)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810aac1f)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810b3982)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d6de0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mempolicy.c (ffffffff81293607)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (ffffffff81302050)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/crypto/keyring.c (ffffffff813451c1)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81378270)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/dir.c (ffffffff813fd150)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff81414db2)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff814febe0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (ffffffff81685241)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/nvme/host/lightnvm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/tun.c (ffffffff817894e0)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817b3280)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (ffffffff818b6c43)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff818c974a)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (ffffffff818f5b20)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81955be6)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff8195e951)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819fdcd0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a1c13a)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff81a2c573)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffffffff81a32270)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/wireless/wext-priv.c (ffffffff81a33420)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
**Symbols:**

```
ffffffff811d6de0-ffffffff811d6df9: copy_overflow (STB_LOCAL)
ffffffff81302050-ffffffff81302069: copy_overflow (STB_LOCAL)
ffffffff81378270-ffffffff81378289: copy_overflow (STB_LOCAL)
ffffffff813fd150-ffffffff813fd169: copy_overflow (STB_LOCAL)
ffffffff814febe0-ffffffff814febf9: copy_overflow (STB_LOCAL)
ffffffff817b3280-ffffffff817b3299: copy_overflow (STB_LOCAL)
ffffffff818f5b20-ffffffff818f5b39: copy_overflow (STB_LOCAL)
ffffffff819fdcd0-ffffffff819fdce9: copy_overflow (STB_LOCAL)
ffffffff81a29230-ffffffff81a29249: copy_overflow (STB_LOCAL)
ffffffff81a32270-ffffffff81a32289: copy_overflow (STB_LOCAL)
ffffffff81a33420-ffffffff81a33439: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/umip.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/ptrace.c (ffffffff81096306)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810995bf)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810a22b2)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811c9ba0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mempolicy.c (ffffffff81285217)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (ffffffff812f2c70)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/crypto/keyring.c (ffffffff81335ea1)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81368d40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/dir.c (ffffffff813edbd0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff81405832)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff814ef0f0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (ffffffff81662ee1)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/tun.c (ffffffff81768e30)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_igd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817a4cb0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (ffffffff81870b93)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff8188368a)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (ffffffff818af950)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190f6d6)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81918441)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819baa90)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d8efa)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff819e9763)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffffffff819ef510)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
**Symbols:**

```
ffffffff811c9ba0-ffffffff811c9bb9: copy_overflow (STB_LOCAL)
ffffffff812f2c70-ffffffff812f2c89: copy_overflow (STB_LOCAL)
ffffffff81368d40-ffffffff81368d59: copy_overflow (STB_LOCAL)
ffffffff813edbd0-ffffffff813edbe9: copy_overflow (STB_LOCAL)
ffffffff814ef0f0-ffffffff814ef109: copy_overflow (STB_LOCAL)
ffffffff817a4cb0-ffffffff817a4cc9: copy_overflow (STB_LOCAL)
ffffffff818af950-ffffffff818af969: copy_overflow (STB_LOCAL)
ffffffff819baa90-ffffffff819baaa9: copy_overflow (STB_LOCAL)
ffffffff819e6420-ffffffff819e6439: copy_overflow (STB_LOCAL)
ffffffff819ef510-ffffffff819ef529: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/umip.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/ptrace.c (ffffffff810a6e86)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810aa17f)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810b2ee2)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d4bb0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mempolicy.c (ffffffff81291417)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (ffffffff812ffe40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/crypto/keyring.c (ffffffff81342c91)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81375d40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/dir.c (ffffffff813fa4d0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff81412132)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff814fac70)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (ffffffff816b3631)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/tun.c (ffffffff817b9880)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_igd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817efd20)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (ffffffff81907c43)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff8191a74a)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (ffffffff81946b50)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/netfilter/nf_conntrack_proto.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c03b6)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff819c9121)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a68750)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a86bba)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff81a98123)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffffffff81a9de20)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/wireless/wext-priv.c (ffffffff81a9f2d0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
**Symbols:**

```
ffffffff811d4bb0-ffffffff811d4bc9: copy_overflow (STB_LOCAL)
ffffffff812ffe40-ffffffff812ffe59: copy_overflow (STB_LOCAL)
ffffffff81375d40-ffffffff81375d59: copy_overflow (STB_LOCAL)
ffffffff813fa4d0-ffffffff813fa4e9: copy_overflow (STB_LOCAL)
ffffffff814fac70-ffffffff814fac89: copy_overflow (STB_LOCAL)
ffffffff817efd20-ffffffff817efd39: copy_overflow (STB_LOCAL)
ffffffff81946b50-ffffffff81946b69: copy_overflow (STB_LOCAL)
ffffffff81a68750-ffffffff81a68769: copy_overflow (STB_LOCAL)
ffffffff81a94de0-ffffffff81a94df9: copy_overflow (STB_LOCAL)
ffffffff81a9de20-ffffffff81a9de39: copy_overflow (STB_LOCAL)
ffffffff81a9f2d0-ffffffff81a9f2e9: copy_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void copy_overflow(int size, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/kernel/umip.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/mm/pkeys.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/exit.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/capability.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/ptrace.c (ffffffff810af156)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffffffff810b235f)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
```
In kernel/sys.c (ffffffff810bb902)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kcmp.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In kernel/profile.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e2ee0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In kernel/rseq.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/shmem.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In mm/util.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/mempolicy.c (ffffffff812a1225)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/exec.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/xattr.c (ffffffff81311180)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/utimes.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/crypto/keyring.c (ffffffff81355f91)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/verity/measure.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/quota/quota.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813897f0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/dir.c (ffffffff81410130)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In fs/fat/file.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In fs/ecryptfs/miscdev.c (ffffffff81427d9d)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/syscall.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/compat_dh.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff81513d20)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/blk-mq-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/random.c (ffffffff816cdbb1)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/mfd/ab3100-core.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/net/tun.c (ffffffff817d52a5)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/vfio/pci/vfio_pci_igd.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81809f60)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/rtc/dev.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/pps/pps.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/socket.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sock.c (ffffffff81928c74)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff8193b994)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/filter.c (ffffffff81968460)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c9d94)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff819d2c71)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a74d40)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a9377a)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffffffff81aa4993)
Location: include/linux/thread_info.h:132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffffffff81aaa020)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/wireless/wext-priv.c (ffffffff81aab4d0)
Location: include/linux/thread_info.h:132
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
```
In lib/seq_buf.c (0)
Location: include/linux/thread_info.h:132
Inline: True
```
**Symbols:**

```
ffffffff811e2ee0-ffffffff811e2ef9: copy_overflow (STB_LOCAL)
ffffffff81311180-ffffffff81311199: copy_overflow (STB_LOCAL)
ffffffff813897f0-ffffffff81389809: copy_overflow (STB_LOCAL)
ffffffff81410130-ffffffff81410149: copy_overflow (STB_LOCAL)
ffffffff81513d20-ffffffff81513d39: copy_overflow (STB_LOCAL)
ffffffff81809f60-ffffffff81809f79: copy_overflow (STB_LOCAL)
ffffffff81968460-ffffffff81968479: copy_overflow (STB_LOCAL)
ffffffff81a74d40-ffffffff81a74d59: copy_overflow (STB_LOCAL)
ffffffff81aa10b0-ffffffff81aa10c9: copy_overflow (STB_LOCAL)
ffffffff81aaa020-ffffffff81aaa039: copy_overflow (STB_LOCAL)
ffffffff81aab4d0-ffffffff81aab4e9: copy_overflow (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
