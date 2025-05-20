# Function: <code>compat_ptr</code>

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
In arch/x86/events/core.c (ffffffff810077bc)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal_compat.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810780e3)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In kernel/ptrace.c (ffffffff8108b2f8)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In kernel/power/user.c (ffffffff810d5e1a)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex_compat.c (ffffffff811031d7)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
```
In kernel/kexec.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In kernel/compat.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In kernel/seccomp.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In fs/exec.c (ffffffff81212ddb)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In fs/splice.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In fs/compat.c (ffffffff81264553)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_fcntl
```
```
In fs/compat_ioctl.c (ffffffff81265c7b)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff812a1747)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In fs/fuse/file.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In ipc/compat.c (ffffffff81323296)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_msgsnd
```
```
In ipc/compat_mq.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In security/keys/compat.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In block/compat_ioctl.c (ffffffff813e55a4)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146d0f9)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff814efeaf)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff81519d37)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In net/socket.c (ffffffff816fbd16)
Location: arch/x86/include/asm/compat.h:286
Inline: True
Inline callers:
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
```
```
In net/compat.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: arch/x86/include/asm/compat.h:286
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: arch/x86/include/asm/compat.h:286
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
In arch/x86/events/core.c (ffffffff810079a5)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102e07b)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:297
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810795ba)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff8108d053)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:compat_SyS_sysctl
  - kernel/sysctl_binary.c:compat_SyS_sysctl
```
```
In kernel/ptrace.c (ffffffff8108f4e4)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81094d1d)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - kernel/signal.c:compat_restore_altstack
```
```
In kernel/power/user.c (ffffffff810dad67)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex_compat.c (ffffffff8110a6e4)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
```
In kernel/kexec.c (ffffffff81115a89)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
```
In kernel/compat.c (ffffffff81119293)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_move_pages
```
```
In kernel/seccomp.c (ffffffff811440c1)
Location: arch/x86/include/asm/compat.h:297
Inline: True
```
```
In fs/exec.c (ffffffff81239c08)
Location: arch/x86/include/asm/compat.h:297
Inline: True
```
```
In fs/splice.c (ffffffff81267b38)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - fs/splice.c:compat_SyS_vmsplice
```
```
In fs/compat.c (ffffffff81290f97)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_io_submit
  - fs/compat.c:compat_SyS_fcntl
```
```
In fs/compat_ioctl.c (ffffffff81291e66)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff812d0587)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (0)
Location: arch/x86/include/asm/compat.h:297
Inline: True
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:297
Inline: True
```
```
In fs/fuse/file.c (ffffffff8134a98f)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/compat.c (ffffffff813591a6)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - ipc/compat.c:compat_SyS_shmat
  - ipc/compat.c:compat_SyS_msgrcv
  - ipc/compat.c:compat_SyS_msgsnd
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:do_compat_semctl
```
```
In ipc/compat_mq.c (ffffffff813633ca)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_notify
```
```
In security/keys/compat.c (ffffffff8136a8f8)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
```
In block/compat_ioctl.c (ffffffff8142c270)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/compat.h:297
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814bb419)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:297
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81540abf)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff8156ca37)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:297
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:297
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8167e156)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff816ca4be)
Location: arch/x86/include/asm/compat.h:297
Inline: True
```
```
In drivers/input/evdev.c (ffffffff816cf216)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff816d2ef8)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:297
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8170a708)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff81762a85)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
```
```
In net/compat.c (ffffffff817ac6d2)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff817f1db6)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv6/raw.c (ffffffff818536f6)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff8187c051)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff8187cd42)
Location: arch/x86/include/asm/compat.h:297
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff810079f2)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102df6b)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d3aa)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff81091fd3)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:compat_SyS_sysctl
  - kernel/sysctl_binary.c:compat_SyS_sysctl
```
```
In kernel/ptrace.c (ffffffff81094464)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81099d2d)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/signal.c:compat_restore_altstack
```
```
In kernel/power/user.c (ffffffff810e1837)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex_compat.c (ffffffff81111ee4)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
```
In kernel/kexec.c (ffffffff8111d1a9)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
```
In kernel/compat.c (ffffffff81120c13)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_move_pages
```
```
In kernel/seccomp.c (ffffffff8114df70)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In fs/exec.c (ffffffff8124c947)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In fs/splice.c (ffffffff8127aaa8)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/splice.c:compat_SyS_vmsplice
```
```
In fs/aio.c (ffffffff8129a466)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/aio.c:compat_SyS_io_submit
```
```
In fs/compat.c (ffffffff812a5d27)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_fcntl
```
```
In fs/compat_ioctl.c (ffffffff812a6be6)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff812e6327)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In fs/fuse/file.c (ffffffff81360255)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/compat.c (ffffffff8136f696)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - ipc/compat.c:compat_SyS_shmat
  - ipc/compat.c:compat_SyS_msgrcv
  - ipc/compat.c:compat_SyS_msgsnd
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:do_compat_semctl
```
```
In ipc/compat_mq.c (ffffffff81379b9a)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_notify
```
```
In security/keys/compat.c (ffffffff81381108)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
```
In block/compat_ioctl.c (ffffffff81446070)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814dd419)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8156d0ff)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff815991a7)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff816abed6)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff816f855e)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In drivers/input/evdev.c (ffffffff816fcee6)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff81702b38)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8173c5d8)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff8178fb75)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
```
```
In net/compat.c (ffffffff817dbcf2)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff81822ba6)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv6/raw.c (ffffffff81885406)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff818b0911)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff818b15f2)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff81007763)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102c1db)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107bbaa)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff8108f179)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:compat_SyS_sysctl
  - kernel/sysctl_binary.c:compat_SyS_sysctl
  - kernel/sysctl_binary.c:compat_SyS_sysctl
```
```
In kernel/ptrace.c (ffffffff81091544)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81096dfb)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - kernel/signal.c:compat_restore_altstack
```
```
In kernel/power/user.c (ffffffff810e0777)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex_compat.c (ffffffff81113510)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
```
In kernel/kexec.c (ffffffff8111edc8)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
```
In kernel/compat.c (ffffffff811213f3)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_move_pages
```
```
In kernel/seccomp.c (ffffffff811504cb)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In fs/read_write.c (0)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In fs/exec.c (ffffffff81258a13)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In fs/fcntl.c (0)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In fs/select.c (ffffffff8126a915)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_pselect6
```
```
In fs/splice.c (ffffffff81287ee8)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - fs/splice.c:compat_SyS_vmsplice
```
```
In fs/aio.c (ffffffff812a81ab)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - fs/aio.c:compat_SyS_io_submit
```
```
In fs/compat.c (ffffffff812b2f69)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
```
```
In fs/compat_ioctl.c (ffffffff812b31f8)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff81309da8)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (0)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In fs/fuse/file.c (ffffffff81374e61)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/compat.c (ffffffff81382bc6)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - ipc/compat.c:compat_SyS_shmat
  - ipc/compat.c:compat_SyS_msgrcv
  - ipc/compat.c:compat_SyS_msgsnd
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_ipc
```
```
In ipc/mqueue.c (ffffffff8138d8ab)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - ipc/mqueue.c:compat_SyS_mq_notify
```
```
In security/keys/compat.c (ffffffff81394f94)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
```
In security/keys/compat_dh.c (ffffffff81395118)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/compat_ioctl.c (ffffffff814546bc)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e9c10)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff815816b1)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff815acf47)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff816c0f26)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_submiturb_compat
  - drivers/usb/core/devio.c:proc_submiturb_compat
```
```
In drivers/input/input-compat.c (ffffffff8170e0ab)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In drivers/input/evdev.c (ffffffff81712ab6)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff81718328)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:294
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81755ee6)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff817afb01)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
```
```
In net/compat.c (ffffffff817fb2a7)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff81843816)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv6/raw.c (ffffffff818ab7e6)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff818d7291)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff818d7fbc)
Location: arch/x86/include/asm/compat.h:294
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff81007ba9)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102cf4e)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810822ad)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff81096029)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:compat_SyS_sysctl
  - kernel/sysctl_binary.c:compat_SyS_sysctl
  - kernel/sysctl_binary.c:compat_SyS_sysctl
```
```
In kernel/ptrace.c (ffffffff810983ca)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8109db9b)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/signal.c:compat_restore_altstack
```
```
In kernel/power/user.c (ffffffff810e8a3f)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex_compat.c (ffffffff8111eaa0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
```
In kernel/kexec.c (ffffffff8112a548)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
```
In kernel/compat.c (ffffffff8112ca93)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_move_pages
```
```
In kernel/seccomp.c (ffffffff8115c6f0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In fs/read_write.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In fs/exec.c (ffffffff8127ab9e)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In fs/fcntl.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In fs/select.c (ffffffff8128d1bb)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_pselect6
```
```
In fs/splice.c (ffffffff812aaa18)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/splice.c:compat_SyS_vmsplice
```
```
In fs/aio.c (ffffffff812cb75b)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/aio.c:compat_SyS_io_submit
```
```
In fs/compat.c (ffffffff812d6a69)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
  - fs/compat.c:compat_SyS_mount
```
```
In fs/compat_ioctl.c (ffffffff812d6c2d)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff8132e81e)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In fs/fuse/file.c (ffffffff81399b1c)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff813a9a0c)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - ipc/msg.c:compat_SyS_msgrcv
  - ipc/msg.c:compat_SyS_msgsnd
```
```
In ipc/sem.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In ipc/shm.c (ffffffff813af9c6)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - ipc/shm.c:compat_SyS_shmat
```
```
In ipc/syscall.c (ffffffff813afbeb)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - ipc/syscall.c:compat_SyS_ipc
  - ipc/syscall.c:compat_SyS_ipc
  - ipc/syscall.c:compat_SyS_ipc
  - ipc/syscall.c:compat_SyS_ipc
  - ipc/syscall.c:compat_SyS_ipc
  - ipc/syscall.c:compat_SyS_ipc
  - ipc/syscall.c:compat_SyS_ipc
  - ipc/syscall.c:compat_SyS_ipc
  - ipc/syscall.c:compat_SyS_ipc
  - ipc/syscall.c:compat_SyS_ipc
```
```
In ipc/mqueue.c (ffffffff813b2ccb)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - ipc/mqueue.c:compat_SyS_mq_notify
```
```
In security/keys/compat.c (ffffffff813ba6da)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
```
In security/keys/compat_dh.c (ffffffff813ba868)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/compat_ioctl.c (ffffffff8148034c)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151e776)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff815e61d1)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff81613917)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8172c956)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_submiturb_compat
  - drivers/usb/core/devio.c:proc_submiturb_compat
```
```
In drivers/input/input-compat.c (ffffffff8177f2d8)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In drivers/input/evdev.c (ffffffff81783cf6)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff81789538)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff817971ad)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:295
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff817c81b6)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff81827c71)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
```
```
In net/compat.c (ffffffff81878c2f)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff818c3216)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv6/raw.c (ffffffff8192e3a6)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff8195ce61)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff8195db9e)
Location: arch/x86/include/asm/compat.h:295
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff810081dc)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:202
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108596d)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff81099148)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
```
```
In kernel/ptrace.c (ffffffff8109bc08)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8109cbb8)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_from_user32
```
```
In kernel/power/user.c (ffffffff810f0d0f)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex_compat.c (ffffffff8112c05e)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
```
In kernel/kexec.c (ffffffff8113875f)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff8116bcf8)
Location: arch/x86/include/asm/compat.h:202
Inline: True
```
```
In mm/migrate.c (ffffffff8127225e)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
```
In fs/read_write.c (ffffffff8129b41f)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/exec.c (ffffffff812a170b)
Location: arch/x86/include/asm/compat.h:202
Inline: True
```
```
In fs/fcntl.c (ffffffff812aeea1)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/select.c (ffffffff812b3223)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff812f4e81)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/compat.c (ffffffff81301920)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
```
In fs/compat_ioctl.c (ffffffff81302c25)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff8135ce24)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff813aa1b5)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:202
Inline: True
```
```
In fs/fuse/file.c (ffffffff813c87a3)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff813d8d15)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff813dccb4)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff813df919)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff813dfd8a)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
```
In ipc/mqueue.c (ffffffff813e1c70)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff813eb545)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff813eb6c8)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/compat_ioctl.c (ffffffff814b5144)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/compat.h:202
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8155430b)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:202
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8161f48f)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff8164d937)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:202
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:202
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8176b9c5)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_submiturb_compat
  - drivers/usb/core/devio.c:proc_submiturb_compat
```
```
In drivers/input/input-compat.c (ffffffff817c03f1)
Location: arch/x86/include/asm/compat.h:202
Inline: True
```
```
In drivers/input/evdev.c (ffffffff817c4dd5)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff817ca326)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff817d9d07)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:202
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8180fc15)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff81871fc1)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff818ca0c6)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff81918d15)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv6/raw.c (ffffffff81987045)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff819b6681)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff819b73b0)
Location: arch/x86/include/asm/compat.h:202
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff810080bc)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108c6dd)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff810a14c8)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
```
```
In kernel/ptrace.c (ffffffff810a3e12)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810a4e78)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (ffffffff810fc39f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex.c (ffffffff81137917)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
```
```
In kernel/kexec.c (ffffffff81143ff4)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff8117951d)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In mm/migrate.c (ffffffff8128686e)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
```
In fs/read_write.c (ffffffff812b031f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/exec.c (ffffffff812b645b)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fcntl.c (ffffffff812c3faa)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/select.c (ffffffff812c82e3)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff8130a064)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/compat.c (ffffffff81317410)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
```
In fs/compat_ioctl.c (ffffffff813182b5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff81375354)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff813c2f95)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fuse/file.c (ffffffff813e193f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff813f2b95)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff813f7302)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff813fa049)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff813fa525)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
```
In ipc/mqueue.c (ffffffff813fc840)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff81406096)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff814062c8)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/compat_ioctl.c (ffffffff814c8a04)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156bb7c)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff8162f141)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8163c647)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff8166b857)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8178ff55)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_submiturb_compat
  - drivers/usb/core/devio.c:proc_submiturb_compat
```
```
In drivers/input/input-compat.c (ffffffff817e78e1)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/input/evdev.c (ffffffff817ec3a5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff817f19e6)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff81800f17)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8183bc15)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff81891b2f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff818f509c)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff819474e5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv6/raw.c (ffffffff819bd965)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff819ed941)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff819ee670)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff81005a4f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090685)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff810a5f18)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
```
```
In kernel/ptrace.c (ffffffff810a8b36)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810a9b39)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (ffffffff81104bef)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex.c (ffffffff8114289b)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
```
```
In kernel/kexec.c (ffffffff8114f356)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff8118636d)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff812a0e21)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
```
In fs/read_write.c (ffffffff812ccc74)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/exec.c (ffffffff812d31a3)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fcntl.c (ffffffff812e09a2)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/select.c (ffffffff812e4e53)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff8132becc)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/compat.c (ffffffff8133ecde)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
```
In fs/compat_ioctl.c (ffffffff8133fafa)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff8139ea40)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff813ed7f5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fuse/file.c (ffffffff8140d67b)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff8141fb35)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff81423413)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff81426639)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff81426897)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff814294d0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff814331c3)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff814333f9)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/compat_ioctl.c (ffffffff814f73ed)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159be59)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff81662c88)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81670ac8)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff816a13d7)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817cde25)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff81828417)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8182cf45)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff818331c0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff81842224)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8187f835)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff818dbb20)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff81953f2f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff819abb75)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv6/raw.c (ffffffff81a2c445)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff81a5cac9)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81a5d8b0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff810085ca)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810911e5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff810ac4f8)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
```
```
In kernel/ptrace.c (ffffffff810af156)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b0119)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (ffffffff81110f9f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex.c (ffffffff8114bf4d)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
```
In kernel/kexec.c (ffffffff8115b03f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff811920df)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff812b2231)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
```
In fs/read_write.c (ffffffff812de694)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/exec.c (ffffffff812e4d33)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fcntl.c (ffffffff812f2452)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/select.c (ffffffff812f6873)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff8133d3e5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/compat.c (ffffffff813572ce)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
```
In fs/compat_ioctl.c (ffffffff813582d9)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff813b7866)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff81407915)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fuse/file.c (ffffffff814289ef)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff81439955)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff8143d153)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff81440389)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff814405d7)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff81443200)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff8144cf33)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff8144d169)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/compat_ioctl.c (ffffffff81514ea3)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bd459)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff816852f8)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816931dd)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff816c4177)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81781cde)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817feba5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff81859987)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8185e665)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff81864b00)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff81873ba4)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818b16f5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff8190e700)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff8198a485)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff819e2825)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/unix/af_unix.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a62f85)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff81a93749)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81a944e0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff81007634)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user32
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/kernel/ptrace.c (ffffffff810458f9)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810969ee)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff810b40d8)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
```
```
In kernel/ptrace.c (ffffffff810b6e16)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810bee79)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (0)
Location: include/linux/compat.h:947
Inline: True
```
```
In kernel/futex.c (ffffffff8115b9d8)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
```
```
In kernel/kexec.c (ffffffff8116bead)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff811a724d)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff812e77d1)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
```
In fs/read_write.c (ffffffff813153d4)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/exec.c (0)
Location: include/linux/compat.h:947
Inline: True
```
```
In fs/fcntl.c (ffffffff8132a66d)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (ffffffff8132c09d)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
```
In fs/select.c (ffffffff8132eae7)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff813767b5)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/io_uring.c (ffffffff8137b77d)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
```
```
In fs/compat.c (ffffffff8139e57e)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
```
In fs/ext4/ioctl.c (ffffffff81402dca)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff81455405)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fuse/file.c (ffffffff814766ca)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff81489aa5)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff8148dd15)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff814910e9)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff81491397)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff81493b2f)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff8149ed81)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff8149f059)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/ioctl.c (ffffffff8155883e)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:compat_blkdev_ioctl
```
```
In block/scsi_ioctl.c (ffffffff81567208)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - block/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - block/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:get_sg_io_hdr
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/compat.h:947
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff816672f1)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/tty/tty_io.c (ffffffff817367b4)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: include/linux/compat.h:947
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81745bed)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff81778a97)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: include/linux/compat.h:947
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81842f15)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
```
```
In drivers/scsi/sr.c (ffffffff8184a1fc)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81851095)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_compat_ioctl
```
```
In drivers/net/tun.c (0)
Location: include/linux/compat.h:947
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818947c4)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff818ae66e)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/usb/core/devio.c (ffffffff818ce76b)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:proc_bulk_compat
```
```
In drivers/input/input-compat.c (ffffffff8192c409)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
```
```
In drivers/input/evdev.c (ffffffff819310e5)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff81938320)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/rtc/dev.c (ffffffff8193c7e5)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff81947d84)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: include/linux/compat.h:947
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff819815b5)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff819e03fb)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff81a62815)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff81acfe25)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv4/af_inet.c (ffffffff81ae20a5)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
```
```
In net/unix/af_unix.c (0)
Location: include/linux/compat.h:947
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff81b29f25)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
```
```
In net/ipv6/raw.c (ffffffff81b5ba25)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff81b8ebd7)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81b8fad0)
Location: include/linux/compat.h:947
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff81008625)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff810453a9)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81095c0e)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/ptrace.c (ffffffff810b1fdf)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810ba1dc)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (0)
Location: include/linux/compat.h:961
Inline: True
```
```
In kernel/futex.c (ffffffff811584a8)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
```
```
In kernel/kexec.c (ffffffff8116859f)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff811a4969)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff812f2b95)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
```
In fs/exec.c (0)
Location: include/linux/compat.h:961
Inline: True
```
```
In fs/fcntl.c (ffffffff81335bdd)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (ffffffff8133771d)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
```
In fs/select.c (ffffffff8133a392)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff81384437)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/io_uring.c (ffffffff81389b1d)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
```
```
In fs/ext4/ioctl.c (ffffffff81415791)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff814718a5)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fuse/file.c (ffffffff81491122)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff814a70d5)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff814ab455)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff814ae8d9)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff814aebd7)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff814b148f)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff814bc7b1)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff814bca89)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/ioctl.c (ffffffff81574e41)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:compat_blkdev_ioctl
```
```
In block/scsi_ioctl.c (ffffffff81582098)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - block/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - block/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:get_sg_io_hdr
```
```
In lib/iov_iter.c (ffffffff815a4143)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_compat_iovec_from_user
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/compat.h:961
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81687ed1)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/tty/tty_io.c (ffffffff81753304)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: include/linux/compat.h:961
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8176161d)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff8179357a)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: include/linux/compat.h:961
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff818538a5)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
```
```
In drivers/scsi/sr.c (ffffffff8185a579)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81861485)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_compat_ioctl
```
```
In drivers/net/tun.c (0)
Location: include/linux/compat.h:961
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a2ef4)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff818bd3fe)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/usb/core/devio.c (ffffffff818d9d18)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff819338f9)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
```
```
In drivers/input/evdev.c (ffffffff81938689)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff8193e710)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/rtc/dev.c (ffffffff819427d5)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff8194dba3)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: include/linux/compat.h:961
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81985bd5)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff819dfd3a)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:ethtool_ioctl
```
```
In net/core/filter.c (ffffffff81a2f0b0)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/compat.c (ffffffff81a6a935)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff81adbda5)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv4/af_inet.c (ffffffff81aeef25)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
```
```
In net/unix/af_unix.c (0)
Location: include/linux/compat.h:961
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff81b38865)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
```
```
In net/ipv6/raw.c (ffffffff81b6a265)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff81b9e887)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81b9f710)
Location: include/linux/compat.h:961
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff81008ff0)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81046fd9)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109656e)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/ptrace.c (ffffffff810b3620)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810bbd48)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (0)
Location: include/linux/compat.h:999
Inline: True
```
```
In kernel/futex.c (ffffffff81159728)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
```
```
In kernel/kexec.c (ffffffff8116933f)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff811a5459)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff812f8f45)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
```
In fs/exec.c (ffffffff8132e539)
Location: include/linux/compat.h:999
Inline: True
```
```
In fs/fcntl.c (ffffffff8133bd6d)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (ffffffff8133dd19)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
```
In fs/select.c (ffffffff813408d6)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff8138b087)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/io_uring.c (ffffffff813908d8)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
```
```
In fs/ext4/ioctl.c (ffffffff8141b944)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff814772c1)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fuse/ioctl.c (ffffffff814a1d96)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff814ad015)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff814b03f5)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff814b46f8)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff814b49f8)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff814b7311)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff814c2671)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff814c2929)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/ioctl.c (ffffffff8157ced1)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:compat_blkdev_ioctl
```
```
In block/scsi_ioctl.c (ffffffff815898ac)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:get_sg_io_hdr
```
```
In lib/iov_iter.c (ffffffff815ab09a)
Location: include/linux/compat.h:999
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/compat.h:999
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81669c91)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/tty/tty_io.c (ffffffff8173733a)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: include/linux/compat.h:999
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8174537d)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff8177627a)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: include/linux/compat.h:999
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff818372b5)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
```
```
In drivers/scsi/sr.c (ffffffff8183d589)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81844215)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_compat_ioctl
```
```
In drivers/net/tun.c (0)
Location: include/linux/compat.h:999
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81886914)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff818a004e)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/usb/core/devio.c (ffffffff818bd26d)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff81916c19)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
```
```
In drivers/input/evdev.c (ffffffff8191bef9)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff81921f10)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/rtc/dev.c (ffffffff81926011)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff81931333)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: include/linux/compat.h:999
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81969515)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff819c59c0)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/core/filter.c (ffffffff81a15710)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/compat.c (ffffffff81a53065)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff81ac6c45)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv4/af_inet.c (ffffffff81ada6a5)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
```
```
In net/unix/af_unix.c (0)
Location: include/linux/compat.h:999
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff81b2647a)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
```
```
In net/ipv6/raw.c (ffffffff81b58595)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff81b8d967)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81b8e7e0)
Location: include/linux/compat.h:999
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff81009ebf)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104d429)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a650e)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/ptrace.c (ffffffff810c57c0)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810ce7a8)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x64_compat_sys_rt_sigaction
  - kernel/signal.c:__x64_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (0)
Location: include/linux/compat.h:974
Inline: True
```
```
In kernel/futex.c (ffffffff8117e3f8)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
```
```
In kernel/kexec.c (ffffffff8118ecda)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - kernel/kexec.c:__do_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff811ceba9)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff8133dfd7)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In fs/exec.c (ffffffff8137bd50)
Location: include/linux/compat.h:974
Inline: True
```
```
In fs/fcntl.c (ffffffff813899ed)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (ffffffff8138b699)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
```
In fs/select.c (ffffffff8138e2a6)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - fs/select.c:__x64_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x64_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__x64_compat_sys_old_select
  - fs/select.c:__x64_compat_sys_old_select
  - fs/select.c:__x64_compat_sys_old_select
  - fs/select.c:__x64_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff813d8605)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__x64_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/io_uring.c (ffffffff813dde88)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
```
```
In fs/ext4/ioctl.c (ffffffff8146ec68)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff814ce9e1)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fuse/ioctl.c (ffffffff814f9e3b)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff81505505)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - ipc/msg.c:__x64_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__x64_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff815084c5)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff8150cda8)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - ipc/shm.c:__x64_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff8150d0a8)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff8150fc51)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - ipc/mqueue.c:__x64_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff8151b061)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff8151b319)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/ioctl.c (ffffffff815e24d1)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:compat_blkdev_ioctl
```
```
In lib/iov_iter.c (ffffffff816149aa)
Location: include/linux/compat.h:974
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/compat.h:974
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff816dd151)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/tty/tty_io.c (ffffffff817b7d1a)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: include/linux/compat.h:974
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff817c62cd)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff817fc00a)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: include/linux/compat.h:974
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff818af39c)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
```
```
In drivers/net/tun.c (0)
Location: include/linux/compat.h:974
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81918304)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81934781)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/usb/core/devio.c (ffffffff81953410)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff819b8e89)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
```
```
In drivers/input/evdev.c (ffffffff819be5a9)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff819c4ec0)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/rtc/dev.c (ffffffff819c8f81)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff819d460f)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: include/linux/compat.h:974
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81a11785)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff81a75250)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:get_user_ifreq
```
```
In net/core/filter.c (ffffffff81ac7160)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/core/dev_ioctl.c (ffffffff81ad0dec)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifconf
```
```
In net/compat.c (ffffffff81b0bd7f)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff81b85465)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv4/af_inet.c (ffffffff81b99915)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
```
```
In net/unix/af_unix.c (0)
Location: include/linux/compat.h:974
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff81bebeda)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
```
```
In net/ipv6/raw.c (ffffffff81c1f925)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff81c59dd7)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81c5ad70)
Location: include/linux/compat.h:974
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff81009612)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81058e60)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bb762)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/ptrace.c (ffffffff810dcd62)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810e650b)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (0)
Location: include/linux/compat.h:1043
Inline: True
```
```
In kernel/futex/core.c (ffffffff811b2fef)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
```
```
In kernel/kexec.c (ffffffff811be3f1)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - kernel/kexec.c:__do_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff81202cd1)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff813b13b7)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In fs/exec.c (ffffffff813fba17)
Location: include/linux/compat.h:1043
Inline: True
```
```
In fs/fcntl.c (ffffffff8140aa7a)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (ffffffff8140c9e7)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
```
In fs/select.c (ffffffff8140f599)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff81462acb)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/ext4/ioctl.c (ffffffff814ef606)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff8155b26e)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fuse/ioctl.c (ffffffff81589a40)
Location: include/linux/compat.h:1043
Inline: True
```
```
In ipc/msg.c (ffffffff81596ec5)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff8159a53a)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff8159ecb7)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff8159efd9)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff815a2dcd)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff815ae01e)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff815ae4f5)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/ioctl.c (ffffffff81691110)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:compat_blkdev_ioctl
```
```
In io_uring/io_uring.c (ffffffff816c8296)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_compat_recvmsg_copy_hdr
```
```
In lib/iov_iter.c (ffffffff816e171e)
Location: include/linux/compat.h:1043
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/compat.h:1043
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81807068)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/tty/tty_io.c (ffffffff818f2fb5)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: include/linux/compat.h:1043
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff819031cd)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff8193a782)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: include/linux/compat.h:1043
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff819f9cb6)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
```
```
In drivers/net/tun.c (0)
Location: include/linux/compat.h:1043
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6d1bb)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81a8c5df)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/usb/core/devio.c (ffffffff81aac9e8)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff81b18a91)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
```
```
In drivers/input/evdev.c (ffffffff81b1e8f8)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff81b25400)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/rtc/dev.c (ffffffff81b2a171)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff81b372e1)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: include/linux/compat.h:1043
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81b79ee5)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff81be805e)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:get_user_ifreq
```
```
In net/core/filter.c (ffffffff81c42b4f)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/core/dev_ioctl.c (ffffffff81c4e777)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifconf
```
```
In net/compat.c (ffffffff81c924cd)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff81d161c5)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv4/af_inet.c (ffffffff81d2b825)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
```
```
In net/unix/af_unix.c (0)
Location: include/linux/compat.h:1043
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff81d843cc)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
```
```
In net/ipv6/raw.c (ffffffff81dbc555)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff81dfb658)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81dfc88f)
Location: include/linux/compat.h:1043
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/compat.h:1043
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
In arch/x86/events/core.c (ffffffff8100aab2)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal_32.c (ffffffff81055812)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff81066740)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
```
```
In kernel/ptrace.c (ffffffff810fcf96)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810fe754)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (0)
Location: include/linux/compat.h:1041
Inline: True
```
```
In kernel/futex/core.c (ffffffff811f3edf)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
```
```
In kernel/kexec.c (ffffffff812004e1)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - kernel/kexec.c:__do_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff8124ab31)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff81432087)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In fs/exec.c (0)
Location: include/linux/compat.h:1041
Inline: True
```
```
In fs/fcntl.c (ffffffff814952ea)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (ffffffff81497477)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
```
In fs/select.c (ffffffff8149a199)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff814f315b)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/ext4/ioctl.c (ffffffff815898ae)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff815fc08e)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fuse/ioctl.c (ffffffff8163007a)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_copy_ioctl_iovec_old
```
```
In ipc/msg.c (ffffffff8163fe35)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff816437ea)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff81648397)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff81648749)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff8164c90d)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff8165872e)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff81658c25)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/ioctl.c (ffffffff8174fd30)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:compat_blkdev_ioctl
```
```
In io_uring/net.c (ffffffff81795590)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - io_uring/net.c:__io_compat_recvmsg_copy_hdr
```
```
In lib/iov_iter.c (ffffffff817d1d1a)
Location: include/linux/compat.h:1041
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/compat.h:1041
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81935bd8)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/tty/tty_io.c (ffffffff81a4b615)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: include/linux/compat.h:1041
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81a5d1cd)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff81a9abd2)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: include/linux/compat.h:1041
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81b77c06)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
```
```
In drivers/net/tun.c (0)
Location: include/linux/compat.h:1041
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c0013b)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81c0d46a)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/usb/core/devio.c (ffffffff81c34030)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff81caa391)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
```
```
In drivers/input/evdev.c (ffffffff81cb0998)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff81cb8950)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/rtc/dev.c (ffffffff81cbdde1)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff81ccc711)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: include/linux/compat.h:1041
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81d18455)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff81d9473e)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:get_user_ifreq
```
```
In net/core/filter.c (ffffffff81dfa0c1)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/core/dev_ioctl.c (ffffffff81e03817)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifconf
```
```
In net/compat.c (ffffffff81e4db3d)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff81edc355)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv4/af_inet.c (ffffffff81ef3405)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
```
```
In net/unix/af_unix.c (0)
Location: include/linux/compat.h:1041
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff81f51cbc)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
```
```
In net/ipv6/raw.c (ffffffff81f8c515)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff81fd0038)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81fd127f)
Location: include/linux/compat.h:1041
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/compat.h:1041
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
In arch/x86/events/core.c (ffffffff8100a303)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal_32.c (ffffffff81056842)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff81067f00)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
```
```
In kernel/ptrace.c (ffffffff81108fb8)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8111344c)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (0)
Location: include/linux/compat.h:977
Inline: True
```
```
In kernel/futex/core.c (ffffffff8120866f)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
```
```
In kernel/kexec.c (ffffffff81215937)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - kernel/kexec.c:__do_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff81261e31)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff814683fe)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In fs/exec.c (ffffffff814bab24)
Location: include/linux/compat.h:977
Inline: True
```
```
In fs/fcntl.c (ffffffff814ca33a)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (ffffffff814cc57f)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
```
In fs/select.c (ffffffff814cf24c)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff81529f1b)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/ext4/ioctl.c (ffffffff815bff28)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff81634021)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fuse/ioctl.c (ffffffff816680fa)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_copy_ioctl_iovec_old
```
```
In ipc/msg.c (ffffffff81678355)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff8167bd2a)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff816808d7)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff81680e6f)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff8168506d)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff81691010)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff816914c5)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/ioctl.c (ffffffff8178bfb0)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:compat_blkdev_ioctl
```
```
In io_uring/net.c (ffffffff817d618c)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - io_uring/net.c:__io_compat_recvmsg_copy_hdr
```
```
In lib/iov_iter.c (ffffffff8181011f)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_compat_iovec_from_user
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/compat.h:977
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81979ec8)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/tty/tty_io.c (ffffffff81a9584d)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: include/linux/compat.h:977
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81aa781d)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff81ae6462)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: include/linux/compat.h:977
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81bcb16c)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - drivers/scsi/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - drivers/scsi/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
```
```
In drivers/net/tun.c (0)
Location: include/linux/compat.h:977
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6576f)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81c750aa)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/usb/core/devio.c (ffffffff81c9ab1e)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff81d11961)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
```
```
In drivers/input/evdev.c (ffffffff81d17f88)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff81d200b0)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/rtc/dev.c (ffffffff81d256f1)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff81d344e6)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: include/linux/compat.h:977
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/compat.h:977
Inline: True
```
```
In net/socket.c (ffffffff81e02d7e)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:get_user_ifreq
```
```
In net/core/filter.c (ffffffff81e6d4a1)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/core/dev_ioctl.c (ffffffff81e75fe7)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifconf
```
```
In net/compat.c (ffffffff81ea91c6)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff81f3b3f5)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv4/af_inet.c (ffffffff81f52e95)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
```
```
In net/unix/af_unix.c (0)
Location: include/linux/compat.h:977
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff81fb16dc)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
```
```
In net/ipv6/raw.c (ffffffff81fecce5)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff8204baf8)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff8204ce87)
Location: include/linux/compat.h:977
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/compat.h:977
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
In arch/x86/events/core.c (ffffffff8100fa23)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal_32.c (ffffffff8105da92)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_restore_sigcontext
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106f380)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
```
```
In kernel/ptrace.c (ffffffff81112948)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8111ce3c)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (0)
Location: include/linux/compat.h:976
Inline: True
```
```
In kernel/futex/core.c (ffffffff8121f4ff)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
```
```
In kernel/kexec.c (ffffffff8122d8e7)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - kernel/kexec.c:__do_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff8127c060)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff8149705b)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
```
```
In fs/exec.c (ffffffff814ed09e)
Location: include/linux/compat.h:976
Inline: True
```
```
In fs/fcntl.c (ffffffff814fcc0a)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (ffffffff814fee3f)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__do_compat_sys_ioctl
```
```
In fs/select.c (ffffffff81501b8c)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff8155edeb)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/ext4/ioctl.c (ffffffff815f8cc8)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff8166d4f1)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fuse/ioctl.c (ffffffff816a23fa)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_copy_ioctl_iovec_old
```
```
In ipc/msg.c (ffffffff816b4715)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff816b80fa)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff816bccf7)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff816bd28f)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff816c148d)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff816cd5e0)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff816cda95)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/ioctl.c (ffffffff817ce750)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:compat_blkdev_ioctl
```
```
In io_uring/net.c (ffffffff8181a74c)
Location: include/linux/compat.h:976
Inline: True
```
```
In lib/iov_iter.c (ffffffff81856e2f)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_compat_iovec_from_user
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/compat.h:976
Inline: True
```
```
In drivers/video/fbdev/core/fb_chrdev.c (ffffffff819ca368)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_chrdev.c:fb_getput_cmap
  - drivers/video/fbdev/core/fb_chrdev.c:fb_getput_cmap
  - drivers/video/fbdev/core/fb_chrdev.c:fb_getput_cmap
  - drivers/video/fbdev/core/fb_chrdev.c:fb_getput_cmap
  - drivers/video/fbdev/core/fb_chrdev.c:fb_getput_cmap
```
```
In drivers/tty/tty_io.c (ffffffff81ae82ad)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: include/linux/compat.h:976
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81afa2ad)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff81b397f2)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: include/linux/compat.h:976
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81c1fd9c)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - drivers/scsi/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - drivers/scsi/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
```
```
In drivers/gpu/drm/drm_ioc32.c (ffffffff81cb9053)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_getunique
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_version
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_version
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_version
```
```
In drivers/net/tun.c (0)
Location: include/linux/compat.h:976
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1c19f)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81d29aaa)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/usb/core/devio.c (ffffffff81d4f6ee)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff81dc7561)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
```
```
In drivers/input/evdev.c (ffffffff81dcdc38)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff81dd5de0)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/rtc/dev.c (ffffffff81ddb461)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff81dea596)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: include/linux/compat.h:976
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/compat.h:976
Inline: True
```
```
In net/socket.c (ffffffff81ebf77e)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:get_user_ifreq
```
```
In net/core/filter.c (ffffffff81f2cea1)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/core/dev_ioctl.c (ffffffff81f35f94)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifconf
```
```
In net/compat.c (ffffffff81f6bc86)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
  - net/compat.c:__get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff82001515)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/ipv4/af_inet.c (ffffffff820191c5)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
```
```
In net/unix/af_unix.c (0)
Location: include/linux/compat.h:976
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff8207edfc)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
```
```
In net/ipv6/raw.c (ffffffff820ba8e5)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff8211df78)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff8211f327)
Location: include/linux/compat.h:976
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
```
```
In net/mctp/af_mctp.c (0)
Location: include/linux/compat.h:976
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
In arch/arm64/kernel/ptrace.c (ffff80001008e624)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_arch_ptrace
```
```
In arch/arm64/kernel/signal32.c (ffff80001009e044)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In arch/arm64/kernel/perf_callchain.c (ffff8000100a382c)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
```
```
In kernel/sysctl_binary.c (ffff8000101056fc)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
```
```
In kernel/ptrace.c (ffff800010109d68)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffff80001010c13c)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/futex.c (ffff8000101b771c)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - kernel/futex.c:compat_fetch_robust_entry
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
```
In kernel/kexec.c (ffff8000101ca4d4)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffff8000102099c8)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffff800010352964)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - mm/migrate.c:__arm64_compat_sys_move_pages
```
```
In fs/read_write.c (0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In fs/exec.c (ffff80001038d6ac)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In fs/fcntl.c (ffff80001039c630)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In fs/select.c (ffff8000103a3be0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - fs/select.c:__arm64_compat_sys_old_select
  - fs/select.c:__arm64_compat_sys_old_select
  - fs/select.c:__arm64_compat_sys_old_select
  - fs/select.c:__arm64_compat_sys_old_select
```
```
In fs/aio.c (ffff8000103fcd60)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_compat_sys_io_submit
```
```
In fs/compat.c (ffff800010419fec)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - fs/compat.c:__arm64_compat_sys_mount
  - fs/compat.c:__arm64_compat_sys_mount
  - fs/compat.c:__arm64_compat_sys_mount
  - fs/compat.c:__arm64_compat_sys_mount
  - fs/compat.c:__arm64_compat_sys_mount
```
```
In fs/compat_ioctl.c (ffff80001041d1e0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_build_iovec
```
```
In fs/ext4/ioctl.c (ffff80001048d3b0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffff8000104e689c)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fat/file.c (0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In fs/fuse/file.c (ffff80001050ad98)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffff80001051fdd0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - ipc/msg.c:__arm64_compat_sys_msgrcv
  - ipc/msg.c:compat_ksys_msgsnd
```
```
In ipc/sem.c (ffff800010524fdc)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffff800010528a30)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - ipc/shm.c:__arm64_compat_sys_shmat
```
```
In ipc/mqueue.c (ffff80001052c414)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - ipc/mqueue.c:__arm64_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffff800010536edc)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffff8000105371b0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/compat_ioctl.c (ffff80001061c0d8)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_put_uint
  - block/compat_ioctl.c:compat_put_int
  - block/compat_ioctl.c:compat_put_ushort
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffff800010746470)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/tty/tty_io.c (ffff80001085314c)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffff800010866fb4)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In drivers/scsi/sd.c (ffff800010987d70)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
```
```
In drivers/net/tun.c (0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In drivers/usb/core/devio.c (ffff800010a32ad4)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:proc_bulk_compat
```
```
In drivers/input/input-compat.c (ffff800010a995f8)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In drivers/input/evdev.c (ffff800010aa0a44)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffff800010aa6148)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffff800010ab8788)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffff800010b09a54)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In drivers/mmc/core/block.c (0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In net/socket.c (ffff800010ba6c4c)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffff800010c330dc)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffff800010c966fc)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/unix/af_unix.c (0)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
```
```
In net/ipv6/raw.c (ffff800010d28204)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffff800010d61930)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffff800010d62c90)
Location: arch/arm64/include/asm/compat.h:123
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/powerpc/kernel/signal_32.c (c00000000001f1c0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn
```
```
In arch/powerpc/kernel/ptrace32.c (c000000000035448)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
```
```
In kernel/sysctl_binary.c (c00000000014cd50)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__se_compat_sys_sysctl
  - kernel/sysctl_binary.c:__se_compat_sys_sysctl
```
```
In kernel/ptrace.c (c000000000150ee0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (c00000000015295c)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/futex.c (c00000000021f770)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
```
In kernel/kexec.c (c000000000232f20)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - kernel/kexec.c:__se_compat_sys_kexec_load
```
```
In kernel/seccomp.c (c000000000286be4)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (c0000000004393a0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - mm/migrate.c:__se_compat_sys_move_pages
```
```
In fs/read_write.c (c00000000047ab5c)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/exec.c (c0000000004843a4)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
```
```
In fs/fcntl.c (c000000000497478)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
```
```
In fs/select.c (c00000000049d9c4)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - fs/select.c:__se_compat_sys_old_select
  - fs/select.c:__se_compat_sys_old_select
  - fs/select.c:__se_compat_sys_old_select
  - fs/select.c:__se_compat_sys_old_select
```
```
In fs/aio.c (c000000000505944)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - fs/aio.c:__se_compat_sys_io_pgetevents_time64
  - fs/aio.c:__se_compat_sys_io_pgetevents
  - fs/aio.c:__se_compat_sys_io_submit
```
```
In fs/compat.c (c000000000529a98)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - fs/compat.c:__se_compat_sys_mount
  - fs/compat.c:__se_compat_sys_mount
  - fs/compat.c:__se_compat_sys_mount
  - fs/compat.c:__se_compat_sys_mount
  - fs/compat.c:__se_compat_sys_mount
```
```
In fs/compat_ioctl.c (c00000000052b260)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
```
```
In fs/ext4/ioctl.c (c0000000005b40f0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (c0000000006247d4)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fat/file.c (0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
```
```
In fs/fuse/file.c (c0000000006531e0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (c00000000066a380)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - ipc/msg.c:__se_compat_sys_msgrcv
  - ipc/msg.c:compat_ksys_msgsnd
```
```
In ipc/sem.c (c00000000066e1b0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (c0000000006736ac)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - ipc/shm.c:__se_compat_sys_shmat
```
```
In ipc/syscall.c (c000000000673f68)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (c000000000677ff0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_compat_sys_mq_notify
```
```
In security/keys/compat.c (c000000000685990)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (c000000000685f04)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/compat_ioctl.c (c0000000007ba990)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_put_uint
  - block/compat_ioctl.c:compat_put_int
  - block/compat_ioctl.c:compat_put_ushort
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (c0000000008a6cd0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/tty/tty_io.c (c0000000008f17a8)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (c00000000090669c)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
```
```
In drivers/scsi/sd.c (c000000000a4874c)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
```
```
In drivers/net/tun.c (0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
```
```
In drivers/usb/core/devio.c (c000000000af02fc)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:proc_bulk_compat
```
```
In drivers/input/input-compat.c (c000000000b795a0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
```
```
In drivers/input/evdev.c (c000000000b80f20)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (c000000000b86950)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (c000000000b9b764)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
```
```
In drivers/md/dm-ioctl.c (c000000000bfb35c)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (c000000000c7ac90)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (c000000000d2c050)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (c000000000da80e4)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/unix/af_unix.c (0)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
```
```
In net/ipv6/raw.c (c000000000e594a4)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (c000000000e9cc70)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (c000000000e9e010)
Location: arch/powerpc/include/asm/compat.h:106
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810085ca)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810901a5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff810a6887)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
```
```
In kernel/ptrace.c (ffffffff810a94c6)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810aa489)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (ffffffff8110957f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex.c (ffffffff8114456d)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
```
In kernel/kexec.c (ffffffff8115365f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff8118a6ff)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff812aa811)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
```
In fs/read_write.c (ffffffff812d6c74)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/exec.c (ffffffff812dd313)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fcntl.c (ffffffff812eaa32)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/select.c (ffffffff812eee53)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff813359c5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/compat.c (ffffffff8134f8ae)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
```
In fs/compat_ioctl.c (ffffffff813508b9)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff813afe46)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff813ffef5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fuse/file.c (ffffffff81420fcf)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff81431f35)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff81435733)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff81438969)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff81438bb7)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff8143b7e0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff81445513)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff81445749)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/compat_ioctl.c (ffffffff8150d483)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b15a9)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff8164ad78)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81658c5d)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff81689bc7)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff817363ce)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817b6f85)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff8180e997)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/input/evdev.c (ffffffff81813675)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff818177b0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81857575)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff818ae700)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff8192a2f5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff81982695)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/unix/af_unix.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a02615)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff81a32dd9)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81a33870)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff81006dba)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107ecb5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff81095267)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
```
```
In kernel/ptrace.c (ffffffff81097e86)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81098e39)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (ffffffff810fa45f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex.c (ffffffff81136d9d)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
```
In kernel/kexec.c (ffffffff8114697f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff8117d829)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff8129c171)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
```
In fs/read_write.c (ffffffff812c78f4)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/exec.c (ffffffff812cdf93)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fcntl.c (ffffffff812db672)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/select.c (ffffffff812dfa83)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff81326205)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/compat.c (ffffffff8134058e)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
```
In fs/compat_ioctl.c (ffffffff81341599)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff813a08d6)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff813f0975)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fuse/file.c (ffffffff81411a4f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff814229b5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff814261b3)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff814293d9)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff81429627)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff8142c250)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff81435f63)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff81436199)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/compat_ioctl.c (ffffffff814fd8b3)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815a0739)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff8162b1c8)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81638fdd)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff81667607)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8171806e)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817a89a5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff817d60e7)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/input/evdev.c (ffffffff817dada5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff817deea0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8181eb85)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff81868650)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff818e40a5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff8193c155)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/unix/af_unix.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819bf3d5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff819eff99)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
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
In arch/x86/events/core.c (ffffffff8100858a)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090155)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff810a5dc8)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
```
```
In kernel/ptrace.c (ffffffff810a8a26)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810a99e9)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (ffffffff8110746f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex.c (ffffffff8114241d)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
```
In kernel/kexec.c (ffffffff8115150f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff811884cf)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff812a8621)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
```
In fs/read_write.c (ffffffff812d4a84)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/exec.c (ffffffff812db123)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fcntl.c (ffffffff812e8842)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/select.c (ffffffff812ecc63)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff81333495)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/compat.c (ffffffff8134d37e)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
```
In fs/compat_ioctl.c (ffffffff8134e389)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff813ad6a6)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff813fd275)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fuse/file.c (ffffffff8141d16f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff8142e0d5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff814318d3)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff81434b09)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff81434d57)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff81437980)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff814415b3)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff814417e9)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/compat_ioctl.c (ffffffff81509513)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b1b39)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff81679138)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8168701d)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff816b7e37)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81776b5e)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817f3a25)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff8184db17)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/input/evdev.c (ffffffff818527f5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff81858c90)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff81867d34)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818a6ba5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff818ff700)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff8197b485)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff819ece65)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/unix/af_unix.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a6d095)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff81a9e989)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81a9f720)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/events/core.c (ffffffff810086ea)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81092535)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/sysctl_binary.c (ffffffff810ade88)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
```
```
In kernel/ptrace.c (ffffffff810b0b46)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b1e39)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (ffffffff8111282f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/futex.c (ffffffff8114e496)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
```
In kernel/kexec.c (ffffffff8115e32f)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
```
In kernel/seccomp.c (ffffffff81195e24)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/migrate.c (ffffffff812b8941)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
```
In fs/read_write.c (ffffffff812e58e4)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/exec.c (ffffffff812ec0dd)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fcntl.c (ffffffff812f9812)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
```
In fs/ioctl.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/select.c (ffffffff812fdc63)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
```
In fs/aio.c (ffffffff813464e5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
```
In fs/compat.c (ffffffff813608fe)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
```
In fs/compat_ioctl.c (ffffffff81361909)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/ext4/ioctl.c (ffffffff813c2066)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/fat/dir.c (ffffffff81412ea5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
```
```
In fs/fat/file.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In fs/fuse/file.c (ffffffff81433ef5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In ipc/msg.c (ffffffff81444b25)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
```
In ipc/sem.c (ffffffff814489a3)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff8144bc49)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
```
```
In ipc/syscall.c (ffffffff8144be97)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
```
In ipc/mqueue.c (ffffffff8144f080)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
```
In security/keys/compat.c (ffffffff814588c3)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
```
In security/keys/compat_dh.c (ffffffff81458af9)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In block/compat_ioctl.c (ffffffff81522b83)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb5a9)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff81692d78)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
```
```
In drivers/tty/pty.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816a160d)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/char/hpet.c (ffffffff816d2677)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
```
```
In drivers/block/loop.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8179093e)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
```
```
In drivers/net/tun.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8180dca5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/input/input-compat.c (ffffffff81868ce7)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8186d965)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_ioctl_compat
```
```
In drivers/input/misc/uinput.c (ffffffff81873d70)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_compat_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffffffff81882fe4)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
```
```
In drivers/md/md.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818c2de5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
```
In net/socket.c (ffffffff819206f0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff8199d9d5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In net/ipv4/raw.c (ffffffff819f6d55)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_ioctl
```
```
In net/unix/af_unix.c (0)
Location: arch/x86/include/asm/compat.h:187
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a796b5)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/ipv6/raw.c:compat_rawv6_ioctl
```
```
In net/wireless/wext-core.c (ffffffff81aaab89)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81aab920)
Location: arch/x86/include/asm/compat.h:187
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
```
</details>
</li>
</ul>

## Differences
