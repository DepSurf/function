# Function: <code>in_x32_syscall</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108e2d6)
Location: arch/x86/include/asm/compat.h:321
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/auditsc.c (ffffffff81131ad8)
Location: arch/x86/include/asm/compat.h:321
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81144499)
Location: arch/x86/include/asm/compat.h:321
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116c584)
Location: arch/x86/include/asm/compat.h:321
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/ext4/dir.c (ffffffff812be0ca)
Location: arch/x86/include/asm/compat.h:321
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
In drivers/input/input.c (ffffffff816c83c9)
Location: arch/x86/include/asm/compat.h:321
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff816ca3da)
Location: arch/x86/include/asm/compat.h:321
Inline: True
```
```
In drivers/input/evdev.c (ffffffff816cdcb3)
Location: arch/x86/include/asm/compat.h:321
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
In drivers/input/misc/uinput.c (ffffffff816d24f3)
Location: arch/x86/include/asm/compat.h:321
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
In drivers/firmware/efi/efivars.c (ffffffff81736241)
Location: arch/x86/include/asm/compat.h:321
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/kernel/signal_compat.c (ffffffff8102def6)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In kernel/ptrace.c (ffffffff81092f94)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/auditsc.c (ffffffff8113b8ab)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8114e351)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811770eb)
Location: arch/x86/include/asm/compat.h:319
Inline: True
```
```
In fs/ext4/dir.c (ffffffff812d35ba)
Location: arch/x86/include/asm/compat.h:319
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
In drivers/input/input.c (ffffffff816f638c)
Location: arch/x86/include/asm/compat.h:319
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff816f845e)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff816fc087)
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
In drivers/input/misc/uinput.c (ffffffff81701da3)
Location: arch/x86/include/asm/compat.h:319
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
In drivers/firmware/efi/efivars.c (ffffffff81768fca)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/kernel/signal_compat.c (ffffffff8102c166)
Location: arch/x86/include/asm/compat.h:318
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff810312cb)
Location: arch/x86/include/asm/compat.h:318
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff810727f2)
Location: arch/x86/include/asm/compat.h:318
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81075b1b)
Location: arch/x86/include/asm/compat.h:318
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff8108ffa5)
Location: arch/x86/include/asm/compat.h:318
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/auditsc.c (ffffffff8113cf6f)
Location: arch/x86/include/asm/compat.h:318
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811509f3)
Location: arch/x86/include/asm/compat.h:318
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff81179e50)
Location: arch/x86/include/asm/compat.h:318
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/ext4/dir.c (ffffffff812e4f86)
Location: arch/x86/include/asm/compat.h:318
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
In drivers/input/input.c (ffffffff8170bee6)
Location: arch/x86/include/asm/compat.h:318
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8170dfae)
Location: arch/x86/include/asm/compat.h:318
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8171198c)
Location: arch/x86/include/asm/compat.h:318
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
In drivers/input/misc/uinput.c (ffffffff8171758e)
Location: arch/x86/include/asm/compat.h:318
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
In drivers/firmware/efi/efivars.c (ffffffff817879c7)
Location: arch/x86/include/asm/compat.h:318
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/kernel/signal_compat.c (ffffffff8102ced6)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81033515)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff8107806f)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8107bd27)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff81096e51)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/auditsc.c (ffffffff81149d29)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8115d1ec)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811875af)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/ext4/dir.c (ffffffff813099b3)
Location: arch/x86/include/asm/compat.h:319
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
In drivers/input/input.c (ffffffff8177d133)
Location: arch/x86/include/asm/compat.h:319
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8177f1db)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81782bc6)
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
In drivers/input/misc/uinput.c (ffffffff817886eb)
Location: arch/x86/include/asm/compat.h:319
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
In drivers/firmware/efi/efivars.c (ffffffff817fde64)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa7fc)
Location: arch/x86/include/asm/compat.h:319
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/kernel/signal_compat.c (ffffffff8102dfa8)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff810348a1)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff8107ab49)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8107e9b4)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff8109a2fd)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810a2048)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
```
```
In kernel/auditsc.c (ffffffff81158619)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8116c08b)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811967b3)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/ext4/dir.c (ffffffff813379bd)
Location: arch/x86/include/asm/compat.h:226
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
In drivers/input/input.c (ffffffff817be1a3)
Location: arch/x86/include/asm/compat.h:226
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff817c024f)
Location: arch/x86/include/asm/compat.h:226
Inline: True
```
```
In drivers/input/evdev.c (ffffffff817c36ec)
Location: arch/x86/include/asm/compat.h:226
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
In drivers/input/misc/uinput.c (ffffffff817c96bb)
Location: arch/x86/include/asm/compat.h:226
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
In drivers/firmware/efi/efivars.c (ffffffff818475ee)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/xfrm/xfrm_state.c (ffffffff819512fc)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/kernel/signal_compat.c (ffffffff8102f1e8)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81035a81)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff81081489)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81085534)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff810a266f)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810aa17a)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
```
```
In kernel/auditsc.c (ffffffff81165633)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81179aab)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a48f3)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/ext4/dir.c (ffffffff8134ec0d)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/input/input.c (ffffffff817e5603)
Location: arch/x86/include/asm/compat.h:211
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff817e773f)
Location: arch/x86/include/asm/compat.h:211
Inline: True
```
```
In drivers/input/evdev.c (ffffffff817ea98f)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/input/misc/uinput.c (ffffffff817f0d6b)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/firmware/efi/efivars.c (ffffffff8187384e)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/xfrm/xfrm_state.c (ffffffff819847dc)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/kernel/signal_compat.c (ffffffff81030fb8)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81037bf0)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff810850f9)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8108912c)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff810a7303)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810afe4f)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user_any
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
```
```
In kernel/time/time.c (ffffffff81126b8f)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff81172193)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81186164)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b2833)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/io_uring.c (ffffffff813310c0)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff81377a47)
Location: arch/x86/include/asm/compat.h:211
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
In fs/fuse/file.c (ffffffff8140cee9)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/input/input.c (ffffffff81825d60)
Location: arch/x86/include/asm/compat.h:211
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8182832b)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8182b2d9)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/input/misc/uinput.c (ffffffff818319fb)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/firmware/efi/efivars.c (ffffffff818b795e)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff818df938)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee4c3)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/kernel/signal_compat.c (ffffffff81031878)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff810383c0)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff81085de9)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81089d9c)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff810ad923)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b646f)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user_any
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
```
```
In kernel/time/time.c (ffffffff81132b2f)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff8117e043)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81191e34)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811bde23)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/io_uring.c (ffffffff81344c64)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff8138fdc7)
Location: arch/x86/include/asm/compat.h:211
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
In fs/fuse/file.c (ffffffff81428344)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/input/input.c (ffffffff81857290)
Location: arch/x86/include/asm/compat.h:211
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8185989b)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8185cc49)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/input/misc/uinput.c (ffffffff8186333b)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/firmware/efi/efivars.c (ffffffff818ea34e)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff81911b08)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff81a253a3)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/kernel/signal.c (ffffffff81033be5)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/signal_compat.c (ffffffff810340d8)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff8103ad7e)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff81089539)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8109168f)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff810b5351)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810be7de)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (0)
Location: arch/x86/include/asm/compat.h:194
Inline: True
```
```
In kernel/time/time.c (ffffffff81141d6f)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff81191433)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811a7044)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d7bbf)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/io_uring.c (ffffffff81385885)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff813db397)
Location: arch/x86/include/asm/compat.h:194
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
In fs/fuse/file.c (ffffffff81475ff2)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In block/scsi_ioctl.c (ffffffff815670f1)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_put_cdrom_generic_arg
  - block/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:put_sg_io_hdr
  - block/scsi_ioctl.c:sg_io
```
```
In drivers/scsi/sg.c (ffffffff8184f4b7)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff8185eeb0)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff818ae913)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/input/input.c (ffffffff81929280)
Location: arch/x86/include/asm/compat.h:194
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8192c3ad)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8192fdee)
Location: arch/x86/include/asm/compat.h:194
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
In drivers/input/misc/uinput.c (ffffffff8193722a)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_from_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_events_to_user
  - drivers/input/misc/uinput.c:uinput_events_to_user
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
```
```
In drivers/firmware/efi/efivars.c (ffffffff819bddbb)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff819e39a7)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17323)
Location: arch/x86/include/asm/compat.h:194
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/kernel/signal.c (ffffffff81034655)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/signal_compat.c (ffffffff81034ad5)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff8103b58e)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff81089719)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81090fbf)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff810b054b)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b9ade)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (0)
Location: arch/x86/include/asm/compat.h:191
Inline: True
```
```
In kernel/time/time.c (ffffffff8113df7f)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff8118e653)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811a4724)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d4c8f)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In mm/process_vm_access.c (ffffffff812b8e08)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In fs/io_uring.c (ffffffff813968b7)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff813ecdc7)
Location: arch/x86/include/asm/compat.h:191
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
In fs/fuse/file.c (ffffffff81490a4b)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In block/scsi_ioctl.c (ffffffff81581f81)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_put_cdrom_generic_arg
  - block/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:put_sg_io_hdr
```
```
In lib/iov_iter.c (ffffffff815a8fb9)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In drivers/scsi/sg.c (ffffffff81861355)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff8186ded9)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff818bd6a3)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/input/input.c (ffffffff81930880)
Location: arch/x86/include/asm/compat.h:191
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8193389d)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff819370b8)
Location: arch/x86/include/asm/compat.h:191
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
In drivers/input/misc/uinput.c (ffffffff8193d61a)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_from_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_events_to_user
  - drivers/input/misc/uinput.c:uinput_events_to_user
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
```
```
In drivers/firmware/efi/efivars.c (ffffffff819bfa3b)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff819e1705)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff819e6b5e)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/core/filter.c (ffffffff81a2f045)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaaa47)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/xfrm/xfrm_state.c (ffffffff81b26409)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5f767)
Location: arch/x86/include/asm/compat.h:191
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
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
In arch/x86/kernel/signal.c (ffffffff810361e5)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/signal_compat.c (ffffffff81036555)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff8103cf6f)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff8108a429)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81091a95)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff810b1acb)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810bb2ce)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (0)
Location: arch/x86/include/asm/compat.h:180
Inline: True
```
```
In kernel/time/time.c (ffffffff8113f1cf)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff8118f5d3)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811a5214)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d64df)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In mm/process_vm_access.c (ffffffff812be2d0)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In fs/io_uring.c (ffffffff81399c71)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff813f32f7)
Location: arch/x86/include/asm/compat.h:180
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
In fs/fuse/ioctl.c (ffffffff814a170b)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In block/scsi_ioctl.c (ffffffff815896dd)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:put_sg_io_hdr
```
```
In lib/iov_iter.c (ffffffff815b3bf9)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In drivers/scsi/sg.c (ffffffff8184403e)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff8185047b)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff818a0303)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/input/input.c (ffffffff81913a02)
Location: arch/x86/include/asm/compat.h:180
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff81916bbd)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8191aa28)
Location: arch/x86/include/asm/compat.h:180
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
In drivers/input/misc/uinput.c (ffffffff8192063a)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_from_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffffffff819a413f)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff819c7755)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff819cc95e)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/core/filter.c (ffffffff81a156a5)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a96017)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81aa3296)
Location: arch/x86/include/asm/compat.h:180
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81b13fa6)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4cc57)
Location: arch/x86/include/asm/compat.h:180
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
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
In arch/x86/kernel/signal.c (ffffffff8103b465)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8103b7f5)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81042a6f)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff81099989)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810a1615)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff810c3bbb)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810cdbde)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:post_copy_siginfo_from_user32
```
```
In kernel/power/user.c (0)
Location: arch/x86/include/asm/compat.h:159
Inline: True
```
```
In kernel/time/time.c (ffffffff8116265f)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff811b84b3)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811ce964)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff8120336f)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In mm/process_vm_access.c (ffffffff81300a70)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In mm/mempolicy.c (ffffffff81327e2c)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_bitmap
```
```
In mm/migrate.c (ffffffff8133dea9)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In fs/io_uring.c (ffffffff813e8d4e)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff81445337)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
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
In fs/fuse/ioctl.c (ffffffff814f97d2)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In lib/iov_iter.c (ffffffff81619d69)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff818af6be)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:put_sg_io_hdr
```
```
In drivers/scsi/sg.c (ffffffff818d0b07)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff818ddc7b)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81934c6c)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/input/input.c (ffffffff819b5ae2)
Location: arch/x86/include/asm/compat.h:159
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff819b8e2d)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff819bcf3b)
Location: arch/x86/include/asm/compat.h:159
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
In drivers/input/misc/uinput.c (ffffffff819c343a)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_from_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffffffff81a513df)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff81a74a1a)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - net/socket.c:put_user_ifreq
  - net/socket.c:get_user_ifreq
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff81a7c09e)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/core/filter.c (ffffffff81ac70f5)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/core/dev_ioctl.c (ffffffff81ad1257)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifconf
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51477)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81b5f46c)
Location: arch/x86/include/asm/compat.h:159
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd80a6)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c13f67)
Location: arch/x86/include/asm/compat.h:159
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
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
In arch/x86/kernel/signal_compat.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/signal.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/power/user.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/time/time.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/auditsc.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/seccomp.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In lib/iov_iter.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/input.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/firmware/efi/efivars.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/socket.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/core/sock.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: arch/x86/include/asm/compat.h:83
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
In arch/x86/kernel/signal_compat.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/signal.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/power/user.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/time/time.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/auditsc.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/seccomp.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In lib/iov_iter.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/input.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/socket.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/core/sock.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: arch/x86/include/asm/compat.h:83
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
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/signal.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/power/user.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/time/time.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/auditsc.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/seccomp.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In lib/iov_iter.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/input.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/socket.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/core/sock.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: arch/x86/include/asm/compat.h:83
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
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/kernel/shstk.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/ptrace.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/signal.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/power/user.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/time/time.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/auditsc.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/seccomp.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In io_uring/register.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In io_uring/futex.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In lib/iov_iter.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/input.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/socket.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/core/sock.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/compat.h:83
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: arch/x86/include/asm/compat.h:83
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff810319d8)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81038520)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff81084de9)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088d5c)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff810a7c93)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b07df)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user_any
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
```
```
In kernel/time/time.c (ffffffff8112b2df)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff81176663)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8118a454)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b6443)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/io_uring.c (ffffffff8133d244)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff813883a7)
Location: arch/x86/include/asm/compat.h:211
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
In fs/fuse/file.c (ffffffff81420924)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/input/input.c (ffffffff8180c2a0)
Location: arch/x86/include/asm/compat.h:211
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8180e8ab)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81811c59)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/input/misc/uinput.c (ffffffff81815feb)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/firmware/efi/efivars.c (ffffffff8188d0ce)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff818b1b08)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff819c4a33)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/kernel/signal_compat.c (ffffffff810213b8)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81027f00)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff81073ab9)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810779bc)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff8109666d)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8109f0ff)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user_any
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
```
```
In kernel/time/time.c (ffffffff8111db4f)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff81169803)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8117d584)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a9243)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/io_uring.c (ffffffff8132df04)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff81378e37)
Location: arch/x86/include/asm/compat.h:211
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
In fs/fuse/file.c (ffffffff814113a4)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/input/input.c (ffffffff817d3a10)
Location: arch/x86/include/asm/compat.h:211
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff817d5ffb)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff817d9399)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/input/misc/uinput.c (ffffffff817dd6eb)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/firmware/efi/efivars.c (ffffffff81844a4e)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff8186ba58)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff81981823)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/kernel/signal_compat.c (ffffffff81031838)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81038380)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff81084d99)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088d0c)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff810a71f3)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810afd3f)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user_any
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
```
```
In kernel/time/time.c (ffffffff81128fff)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff81174433)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81188224)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b4213)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/io_uring.c (ffffffff8133ad14)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff81385d07)
Location: arch/x86/include/asm/compat.h:211
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
In fs/fuse/file.c (ffffffff8141cac4)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/input/input.c (ffffffff8184b420)
Location: arch/x86/include/asm/compat.h:211
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8184da2b)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81850dd9)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/input/misc/uinput.c (ffffffff818574cb)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/firmware/efi/efivars.c (ffffffff818df1ae)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff81902b08)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f4b3)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/kernel/signal_compat.c (ffffffff810326e8)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81039380)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff81086ee9)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8108afac)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff810af531)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b800f)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user_any
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
```
```
In kernel/time/time.c (ffffffff8113564f)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff81181d13)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81195b84)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c22b3)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/io_uring.c (ffffffff8134dec4)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff813999f7)
Location: arch/x86/include/asm/compat.h:211
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
In fs/fuse/file.c (ffffffff814338a4)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/input/input.c (ffffffff81866680)
Location: arch/x86/include/asm/compat.h:211
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff81868bfb)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8186c869)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/input/misc/uinput.c (ffffffff818725eb)
Location: arch/x86/include/asm/compat.h:211
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
In drivers/firmware/efi/efivars.c (ffffffff818fbc4e)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff81923aa8)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3ae03)
Location: arch/x86/include/asm/compat.h:211
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
</details>
</li>
</ul>

## Differences
