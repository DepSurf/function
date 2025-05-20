# Function: <code>__copy_from_user_overflow</code>

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
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In arch/x86/kernel/crash_dump_64.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/sysctl_binary.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/capability.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/ptrace.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/sys.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/power/qos.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/power/user.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/profile.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/time/time.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/time/timer_stats.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/module.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/kexec.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/compat.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/auditsc.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/seccomp.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/relay.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In mm/shmem.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In mm/util.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/read_write.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/stat.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/exec.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/pipe.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/namei.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/fcntl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/readdir.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/select.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/dcache.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/filesystems.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/seq_file.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/xattr.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/libfs.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/splice.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/utimes.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/statfs.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/eventpoll.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/signalfd.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/timerfd.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/eventfd.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/locks.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/compat.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/fhandle.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/quota/quota.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/proc/base.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/dcookies.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/fat/dir.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/fuse/file.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In fs/efivarfs/file.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In ipc/compat.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In ipc/msgutil.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In ipc/msg.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In ipc/sem.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In ipc/shm.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In ipc/mqueue.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In ipc/compat_mq.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/keys/big_key.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/keys/trusted.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/integrity/ima/ima_fs.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In security/integrity/evm/evm_secfs.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In block/ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In block/bsg.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In lib/seq_buf.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In lib/kstrtox.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In lib/dynamic_debug.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/pinctrl/pinconf.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/xen/mcelog.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/tty/tty_ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/char/mem.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/mfd/ab3100-core.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/scsi/scsi_proc.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/rtc/rtc-dev.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/socket.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/core/sock.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/core/scm.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/core/ethtool.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/compat.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/netfilter/nf_log.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv6/route.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
```
In net/rfkill/core.c (0)
Location: arch/x86/include/asm/uaccess.h:683
Inline: True
```
</details>
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
