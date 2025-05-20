# Function: <code>is_compat_task</code>

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
In kernel/ptrace.c (ffffffff8108b254)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/auditsc.c (ffffffff8112990b)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8113b6e6)
Location: arch/x86/include/asm/compat.h:319
Inline: True
```
```
In kernel/trace/trace_syscalls.c (ffffffff81161c7c)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/ext4/dir.c (ffffffff81290a44)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In drivers/input/input.c (ffffffff816683c6)
Location: arch/x86/include/asm/compat.h:319
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8166a0b6)
Location: arch/x86/include/asm/compat.h:319
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8166d944)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff81671cf0)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
```
```
In drivers/firmware/efi/efivars.c (ffffffff816d2256)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/fpsimd.c (ffff8000100884ac)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:do_sve_acc
```
```
In arch/arm64/kernel/process.c (ffff8000100898d0)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:get_tagged_addr_ctrl
  - arch/arm64/kernel/process.c:set_tagged_addr_ctrl
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/process.c:flush_thread
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008eed8)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:syscall_trace_exit
  - arch/arm64/kernel/ptrace.c:syscall_trace_enter
  - arch/arm64/kernel/ptrace.c:task_user_regset_view
  - arch/arm64/kernel/ptrace.c:ptrace_hbptriggered
```
```
In arch/arm64/kernel/signal.c (ffff800010093520)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
```
```
In arch/arm64/kernel/syscall.c (ffff80001009da28)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
```
```
In virt/kvm/kvm_main.c (ffff8000100b4fb8)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_no_compat_open
```
```
In kernel/ptrace.c (ffff8000101076b4)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffff8000101128a8)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
```
```
In kernel/time/time.c (ffff80001019a974)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffff8000101f2e58)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffff8000102097c4)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffff80001023d914)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In mm/util.c (ffff8000102d8a88)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - mm/util.c:arch_mmap_rnd
  - mm/util.c:arch_randomize_brk
```
```
In fs/io_uring.c (ffff800010402ffc)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__arm64_sys_io_uring_enter
```
```
In fs/ext4/dir.c (ffff80001046272c)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In drivers/input/input.c (ffff800010a965f8)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
```
```
In drivers/input/input-compat.c (ffff800010a994d0)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
```
```
In drivers/input/evdev.c (ffff800010a9d66c)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffff800010aa5390)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffff800010b5d4e0)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffff800010baf25c)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_set_timeout
```
```
In net/xfrm/xfrm_state.c (ffff800010ce2854)
Location: arch/arm64/include/asm/compat.h:199
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In kernel/ptrace.c (c00000000014e980)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (c00000000015a2d0)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/time/time.c (c0000000001fa668)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (c000000000267814)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (c000000000286968)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In fs/io_uring.c (c00000000050f968)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__se_sys_io_uring_enter
```
```
In fs/ext4/dir.c (c00000000057ed34)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In drivers/input/input.c (c000000000b75d90)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
```
```
In drivers/input/input-compat.c (c000000000b793cc)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
```
```
In drivers/input/evdev.c (c000000000b7f008)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (c000000000b84dbc)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In net/core/sock.c (c000000000c85038)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_set_timeout
```
```
In net/xfrm/xfrm_state.c (c000000000e058f8)
Location: arch/powerpc/include/asm/compat.h:194
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
