# Function: <code>in_compat_syscall</code>

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
In kernel/ptrace.c (ffffffff8108e2c6)
Location: arch/x86/include/asm/compat.h:330
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/auditsc.c (ffffffff81131abb)
Location: arch/x86/include/asm/compat.h:330
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81144487)
Location: arch/x86/include/asm/compat.h:330
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116c56e)
Location: arch/x86/include/asm/compat.h:330
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/ext4/dir.c (ffffffff812be054)
Location: arch/x86/include/asm/compat.h:330
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
In drivers/input/input.c (ffffffff816c8376)
Location: arch/x86/include/asm/compat.h:330
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff816ca38c)
Location: arch/x86/include/asm/compat.h:330
Inline: True
```
```
In drivers/input/evdev.c (ffffffff816cdc9d)
Location: arch/x86/include/asm/compat.h:330
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
In drivers/input/misc/uinput.c (ffffffff816d244c)
Location: arch/x86/include/asm/compat.h:330
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
In drivers/firmware/efi/efivars.c (ffffffff8173622b)
Location: arch/x86/include/asm/compat.h:330
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
In kernel/ptrace.c (ffffffff81092e96)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/auditsc.c (ffffffff8113b837)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8114e333)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811770d6)
Location: arch/x86/include/asm/compat.h:328
Inline: True
```
```
In fs/ext4/dir.c (ffffffff812d3544)
Location: arch/x86/include/asm/compat.h:328
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
In drivers/input/input.c (ffffffff816f6366)
Location: arch/x86/include/asm/compat.h:328
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff816f844c)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff816fbe4d)
Location: arch/x86/include/asm/compat.h:328
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
In drivers/input/misc/uinput.c (ffffffff81701cfc)
Location: arch/x86/include/asm/compat.h:328
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
In drivers/firmware/efi/efivars.c (ffffffff81768fad)
Location: arch/x86/include/asm/compat.h:328
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
In arch/x86/kernel/sys_x86_64.c (ffffffff810312b9)
Location: arch/x86/include/asm/compat.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff810727df)
Location: arch/x86/include/asm/compat.h:327
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81075aa5)
Location: arch/x86/include/asm/compat.h:327
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff8108ff14)
Location: arch/x86/include/asm/compat.h:327
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/auditsc.c (ffffffff8113cf03)
Location: arch/x86/include/asm/compat.h:327
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811509d5)
Location: arch/x86/include/asm/compat.h:327
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff81179e3e)
Location: arch/x86/include/asm/compat.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/ext4/dir.c (ffffffff812e4f74)
Location: arch/x86/include/asm/compat.h:327
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In drivers/input/input.c (ffffffff8170beb6)
Location: arch/x86/include/asm/compat.h:327
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8170df9c)
Location: arch/x86/include/asm/compat.h:327
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81711710)
Location: arch/x86/include/asm/compat.h:327
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
In drivers/input/misc/uinput.c (ffffffff8171757c)
Location: arch/x86/include/asm/compat.h:327
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
In drivers/firmware/efi/efivars.c (ffffffff8178793d)
Location: arch/x86/include/asm/compat.h:327
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81033506)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff8107805f)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8107bd18)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff81096e42)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/auditsc.c (ffffffff81149cc3)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8115d1d1)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811875a0)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/ext4/dir.c (ffffffff813099a4)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In drivers/input/input.c (ffffffff8177d106)
Location: arch/x86/include/asm/compat.h:328
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8177f1cc)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81782988)
Location: arch/x86/include/asm/compat.h:328
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
In drivers/input/misc/uinput.c (ffffffff817886dc)
Location: arch/x86/include/asm/compat.h:328
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
In drivers/firmware/efi/efivars.c (ffffffff817fdddd)
Location: arch/x86/include/asm/compat.h:328
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa7d5)
Location: arch/x86/include/asm/compat.h:328
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81034892)
Location: arch/x86/include/asm/compat.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/mmap.c (ffffffff8107ab36)
Location: arch/x86/include/asm/compat.h:235
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8107eae6)
Location: arch/x86/include/asm/compat.h:235
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In kernel/ptrace.c (ffffffff8109a282)
Location: arch/x86/include/asm/compat.h:235
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/auditsc.c (ffffffff811585c4)
Location: arch/x86/include/asm/compat.h:235
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8116c070)
Location: arch/x86/include/asm/compat.h:235
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff811967a0)
Location: arch/x86/include/asm/compat.h:235
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/ext4/dir.c (ffffffff81337904)
Location: arch/x86/include/asm/compat.h:235
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In drivers/input/input.c (ffffffff817be175)
Location: arch/x86/include/asm/compat.h:235
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff817c0240)
Location: arch/x86/include/asm/compat.h:235
Inline: True
```
```
In drivers/input/evdev.c (ffffffff817c34b9)
Location: arch/x86/include/asm/compat.h:235
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
In drivers/input/misc/uinput.c (ffffffff817c96ac)
Location: arch/x86/include/asm/compat.h:235
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
In drivers/firmware/efi/efivars.c (ffffffff818475db)
Location: arch/x86/include/asm/compat.h:235
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/xfrm/xfrm_state.c (ffffffff819512f1)
Location: arch/x86/include/asm/compat.h:235
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
In kernel/ptrace.c (ffffffff810a2600)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/auditsc.c (ffffffff811655db)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81179a90)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In fs/ext4/dir.c (ffffffff8134eb54)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In drivers/input/input.c (ffffffff817e55d5)
Location: arch/x86/include/asm/compat.h:226
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff817e7730)
Location: arch/x86/include/asm/compat.h:226
Inline: True
```
```
In drivers/input/evdev.c (ffffffff817ea763)
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
In drivers/input/misc/uinput.c (ffffffff817f0d5c)
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
In drivers/firmware/efi/efivars.c (ffffffff8187383b)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/xfrm/xfrm_state.c (ffffffff819847d1)
Location: arch/x86/include/asm/compat.h:226
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
In kernel/ptrace.c (ffffffff810a729a)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810afe35)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user_any
```
```
In kernel/time/time.c (ffffffff81126b85)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff8117213b)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81186151)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In fs/io_uring.c (ffffffff813310b1)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff81377a33)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In drivers/input/input.c (ffffffff81825d35)
Location: arch/x86/include/asm/compat.h:226
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8182831c)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8182b3a4)
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
In drivers/input/misc/uinput.c (ffffffff818319ec)
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
In drivers/firmware/efi/efivars.c (ffffffff818b794b)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff818df929)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee4b4)
Location: arch/x86/include/asm/compat.h:226
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
In kernel/ptrace.c (ffffffff810ad8ba)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b6455)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user_any
```
```
In kernel/time/time.c (ffffffff81132b25)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff8117dfeb)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81191e21)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In fs/io_uring.c (ffffffff81344c55)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff8138fdb3)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In drivers/input/input.c (ffffffff81857265)
Location: arch/x86/include/asm/compat.h:226
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8185988c)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8185cd14)
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
In drivers/input/misc/uinput.c (ffffffff8186332c)
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
In drivers/firmware/efi/efivars.c (ffffffff818ea33b)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff81911af9)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25394)
Location: arch/x86/include/asm/compat.h:226
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
In kernel/ptrace.c (ffffffff810b52ef)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810be733)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/power/user.c (ffffffff8111bac5)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_set_swap_area
```
```
In kernel/time/time.c (ffffffff81141d65)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff811913db)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811a7031)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In fs/io_uring.c (ffffffff81385871)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff813db383)
Location: arch/x86/include/asm/compat.h:209
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
In block/scsi_ioctl.c (ffffffff815670e2)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_put_cdrom_generic_arg
  - block/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:put_sg_io_hdr
  - block/scsi_ioctl.c:sg_io
```
```
In drivers/scsi/sg.c (ffffffff8184f4a4)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff8185ee5e)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff818ae8fd)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/input/input.c (ffffffff81929255)
Location: arch/x86/include/asm/compat.h:209
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8192c395)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8192fbab)
Location: arch/x86/include/asm/compat.h:209
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
In drivers/input/misc/uinput.c (ffffffff81937174)
Location: arch/x86/include/asm/compat.h:209
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
In drivers/firmware/efi/efivars.c (ffffffff819bdda8)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff819e3998)
Location: arch/x86/include/asm/compat.h:209
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17314)
Location: arch/x86/include/asm/compat.h:209
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
In kernel/ptrace.c (ffffffff810b04df)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b9a33)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/power/user.c (ffffffff81116441)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_set_swap_area
```
```
In kernel/time/time.c (ffffffff8113df75)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff8118e5fb)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811a4711)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In mm/process_vm_access.c (ffffffff812b8d99)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In fs/io_uring.c (ffffffff813968a3)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff813ecdb3)
Location: arch/x86/include/asm/compat.h:206
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
In block/scsi_ioctl.c (ffffffff81581f72)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_put_cdrom_generic_arg
  - block/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:put_sg_io_hdr
```
```
In lib/iov_iter.c (ffffffff815a8fa0)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In drivers/scsi/sg.c (ffffffff818610f0)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff8186de82)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff818bd68d)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/input/input.c (ffffffff81930869)
Location: arch/x86/include/asm/compat.h:206
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff81933885)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81936e7b)
Location: arch/x86/include/asm/compat.h:206
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
In drivers/input/misc/uinput.c (ffffffff8193d564)
Location: arch/x86/include/asm/compat.h:206
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
In drivers/firmware/efi/efivars.c (ffffffff819bfa28)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff819e16f6)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff819e6b4f)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/core/filter.c (ffffffff81a2f036)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaaa32)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/xfrm/xfrm_state.c (ffffffff81b262dc)
Location: arch/x86/include/asm/compat.h:206
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5f758)
Location: arch/x86/include/asm/compat.h:206
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
In kernel/ptrace.c (ffffffff810b1a5f)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810bb223)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/power/user.c (0)
Location: arch/x86/include/asm/compat.h:195
Inline: True
```
```
In kernel/time/time.c (ffffffff8113f1c5)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff8118f57b)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811a5201)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In mm/process_vm_access.c (ffffffff812be262)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In fs/io_uring.c (ffffffff81399c5d)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff813f32e3)
Location: arch/x86/include/asm/compat.h:195
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
In block/scsi_ioctl.c (ffffffff81589683)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:put_sg_io_hdr
```
```
In lib/iov_iter.c (ffffffff815b3be0)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In drivers/scsi/sg.c (ffffffff8184402f)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff818503fa)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff818a02ed)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/input/input.c (ffffffff819139e9)
Location: arch/x86/include/asm/compat.h:195
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff81916ba5)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8191a7eb)
Location: arch/x86/include/asm/compat.h:195
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
In drivers/input/misc/uinput.c (ffffffff81920584)
Location: arch/x86/include/asm/compat.h:195
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
In drivers/firmware/efi/efivars.c (ffffffff819a412c)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff819c7746)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff819cc94f)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/core/filter.c (ffffffff81a15696)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a96008)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81aa328b)
Location: arch/x86/include/asm/compat.h:195
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81b13e7c)
Location: arch/x86/include/asm/compat.h:195
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4cc48)
Location: arch/x86/include/asm/compat.h:195
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
In kernel/ptrace.c (ffffffff810c3b4f)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810cdb33)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/power/user.c (0)
Location: arch/x86/include/asm/compat.h:174
Inline: True
```
```
In kernel/time/time.c (ffffffff81162655)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff811b845b)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811ce951)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In mm/process_vm_access.c (ffffffff81300a02)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In mm/mempolicy.c (ffffffff81327d96)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_bitmap
```
```
In mm/migrate.c (ffffffff8133de98)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In fs/io_uring.c (ffffffff813e8d3a)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff81445323)
Location: arch/x86/include/asm/compat.h:174
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
In lib/iov_iter.c (ffffffff81619d50)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff818af6a0)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:put_sg_io_hdr
```
```
In drivers/scsi/sg.c (ffffffff818d0af8)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff818ddbfa)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81934c56)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/input/input.c (ffffffff819b5ac9)
Location: arch/x86/include/asm/compat.h:174
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff819b8e15)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff819bcc2b)
Location: arch/x86/include/asm/compat.h:174
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
In drivers/input/misc/uinput.c (ffffffff819c3384)
Location: arch/x86/include/asm/compat.h:174
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
In drivers/firmware/efi/efivars.c (ffffffff81a513cc)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff81a749f5)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - net/socket.c:put_user_ifreq
  - net/socket.c:get_user_ifreq
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff81a7c08f)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/core/filter.c (ffffffff81ac70e6)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/core/dev_ioctl.c (ffffffff81ad1240)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifconf
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51468)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81b5f461)
Location: arch/x86/include/asm/compat.h:174
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd7f7c)
Location: arch/x86/include/asm/compat.h:174
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c13f58)
Location: arch/x86/include/asm/compat.h:174
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
In kernel/ptrace.c (ffffffff810db281)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810e5ccf)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/power/user.c (ffffffff811594ec)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In kernel/time/time.c (ffffffff81195e26)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
```
```
In kernel/auditsc.c (ffffffff811eb332)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81202a8c)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In mm/process_vm_access.c (ffffffff81367e21)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In mm/mempolicy.c (ffffffff81396f9a)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
```
```
In mm/migrate.c (ffffffff813b13a4)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In fs/ext4/dir.c (ffffffff814c13fc)
Location: arch/x86/include/asm/compat.h:98
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
In io_uring/io_uring.c (ffffffff81e925a8)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
```
```
In lib/iov_iter.c (ffffffff816e7220)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff819fa6cc)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:put_sg_io_hdr
```
```
In drivers/scsi/sg.c (ffffffff81a1dd14)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2f382)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81a8cb69)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/input/input.c (ffffffff81b1460b)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/input/input.c:input_bits_to_string
```
```
In drivers/input/input-compat.c (ffffffff81b18a25)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81b1d0df)
Location: arch/x86/include/asm/compat.h:98
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
In drivers/input/misc/uinput.c (ffffffff81b23a73)
Location: arch/x86/include/asm/compat.h:98
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
In drivers/firmware/efi/efivars.c (ffffffff81bc01fc)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff81be6055)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/socket.c:put_user_ifreq
  - net/socket.c:get_user_ifreq
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff81bf2c4b)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_copy_user_timeval
```
```
In net/core/filter.c (ffffffff81c42ad1)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/core/dev_ioctl.c (ffffffff81c4ea92)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifconf
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cde300)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81cede88)
Location: arch/x86/include/asm/compat.h:98
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6ee43)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81daf6fc)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
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
In kernel/ptrace.c (ffffffff810fb4e1)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8110688b)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/power/user.c (ffffffff8118b71c)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In kernel/time/time.c (ffffffff811d3da6)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
```
```
In kernel/auditsc.c (ffffffff812316d2)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8124a8ec)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In mm/process_vm_access.c (ffffffff813e3e01)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In mm/mempolicy.c (ffffffff81414b62)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
  - mm/mempolicy.c:get_nodes
```
```
In mm/migrate.c (ffffffff81432074)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In fs/ext4/dir.c (ffffffff8155969c)
Location: arch/x86/include/asm/compat.h:98
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
In io_uring/io_uring.c (ffffffff8178cb64)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
```
```
In lib/iov_iter.c (ffffffff817d6a30)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81b786cf)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
```
```
In drivers/scsi/sg.c (ffffffff81b9f024)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb28d2)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81c0da79)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/input/input.c (ffffffff81ca55bb)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/input/input.c:input_bits_to_string
```
```
In drivers/input/input-compat.c (ffffffff81caa325)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81caf07f)
Location: arch/x86/include/asm/compat.h:98
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
In drivers/input/misc/uinput.c (ffffffff81cb7123)
Location: arch/x86/include/asm/compat.h:98
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
In net/socket.c (ffffffff81d922a5)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/socket.c:put_user_ifreq
  - net/socket.c:get_user_ifreq
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff81da1008)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sock_copy_user_timeval
```
```
In net/core/filter.c (ffffffff81dfa041)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/core/dev_ioctl.c (ffffffff81e03b42)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifconf
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1e3c)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81eb4adf)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3a75c)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f8198b)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
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
In kernel/ptrace.c (ffffffff81107309)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81112b7b)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/power/user.c (ffffffff8119cfaf)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In kernel/time/time.c (ffffffff811e8096)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
```
```
In kernel/auditsc.c (ffffffff81248362)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81261bec)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In mm/process_vm_access.c (ffffffff81418b51)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In mm/mempolicy.c (ffffffff81448119)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
  - mm/mempolicy.c:get_nodes
```
```
In mm/migrate.c (ffffffff814681b0)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In fs/ext4/dir.c (ffffffff815914b2)
Location: arch/x86/include/asm/compat.h:98
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
In io_uring/io_uring.c (ffffffff817cadd5)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_iowq_aff
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
```
```
In lib/iov_iter.c (ffffffff81815a50)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81bcc256)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
```
```
In drivers/scsi/sg.c (ffffffff81bf54f3)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff81c09dc4)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81c75ef9)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/input/input.c (ffffffff81d0ccfb)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/input/input.c:input_bits_to_string
```
```
In drivers/input/input-compat.c (ffffffff81d118f5)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81d1666f)
Location: arch/x86/include/asm/compat.h:98
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
In drivers/input/misc/uinput.c (ffffffff81d1e7c3)
Location: arch/x86/include/asm/compat.h:98
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
In net/socket.c (ffffffff81e00665)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/socket.c:put_user_ifreq
  - net/socket.c:get_user_ifreq
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff81e0f4de)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sock_copy_user_timeval
```
```
In net/core/filter.c (ffffffff81e6d421)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/core/dev_ioctl.c (ffffffff81e764b6)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifconf
```
```
In net/ipv4/ip_sockglue.c (ffffffff81f0059b)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81f12fff)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a17c)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe1cb7)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
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
In kernel/ptrace.c (ffffffff81110c59)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8111c56b)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/power/user.c (ffffffff811ac0ff)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In kernel/time/time.c (ffffffff811fddc6)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
```
```
In kernel/futex/syscalls.c (ffffffff8122003e)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_wait
  - kernel/futex/syscalls.c:__x64_sys_futex_wait
  - kernel/futex/syscalls.c:__ia32_sys_futex_wake
  - kernel/futex/syscalls.c:__x64_sys_futex_wake
  - kernel/futex/syscalls.c:futex_parse_waitv
```
```
In kernel/auditsc.c (ffffffff812621c2)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8127bdec)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In mm/process_vm_access.c (ffffffff814456a1)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In mm/mempolicy.c (ffffffff81481b19)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
  - mm/mempolicy.c:get_nodes
```
```
In mm/migrate.c (ffffffff81496e10)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff814a04be)
Location: arch/x86/include/asm/compat.h:98
Inline: True
```
```
In fs/ext4/dir.c (ffffffff815ca1f2)
Location: arch/x86/include/asm/compat.h:98
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
In io_uring/io_uring.c (ffffffff8181683f)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/register.c (ffffffff8182b3a5)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - io_uring/register.c:io_register_iowq_aff
```
```
In io_uring/futex.c (ffffffff8182f3ef)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_prep
```
```
In lib/iov_iter.c (ffffffff8185ab90)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81c20e86)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
```
```
In drivers/scsi/sg.c (ffffffff81c4ae62)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5ee74)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81d2a8f9)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/input/input.c (ffffffff81dc298b)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/input/input.c:input_bits_to_string
```
```
In drivers/input/input-compat.c (ffffffff81dc74f5)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81dcc2ef)
Location: arch/x86/include/asm/compat.h:98
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
In drivers/input/misc/uinput.c (ffffffff81dd44c3)
Location: arch/x86/include/asm/compat.h:98
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
In net/socket.c (ffffffff81ebcbc5)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/socket.c:put_user_ifreq
  - net/socket.c:get_user_ifreq
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff81ecb393)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sock_copy_user_timeval
```
```
In net/core/filter.c (ffffffff81f2ce21)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/core/dev_ioctl.c (ffffffff81f36463)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifconf
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc45e8)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81fd739a)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff820674dc)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820afbd2)
Location: arch/x86/include/asm/compat.h:98
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
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
In kernel/ptrace.c (ffff8000101076b4)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffff8000101128a8)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
```
```
In kernel/time/time.c (ffff80001019a974)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffff8000101f2e58)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffff8000102097c4)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In fs/io_uring.c (ffff800010402ffc)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__arm64_sys_io_uring_enter
```
```
In fs/ext4/dir.c (ffff80001046272c)
Location: include/linux/compat.h:927
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
Location: include/linux/compat.h:927
Inline: True
```
```
In drivers/input/input-compat.c (ffff800010a994d0)
Location: include/linux/compat.h:927
Inline: True
```
```
In drivers/input/evdev.c (ffff800010a9d66c)
Location: include/linux/compat.h:927
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
Location: include/linux/compat.h:927
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
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffff800010baf25c)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_set_timeout
```
```
In net/xfrm/xfrm_state.c (ffff800010ce2854)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In kernel/auditsc.c (0)
Location: include/linux/compat.h:964
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/compat.h:964
Inline: True
```
```
In drivers/firmware/efi/efivars.c (0)
Location: include/linux/compat.h:964
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/compat.h:964
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/compat.h:964
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
In kernel/ptrace.c (c00000000014e980)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (c00000000015a2d0)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/time/time.c (c0000000001fa668)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (c000000000267814)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (c000000000286968)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In fs/io_uring.c (c00000000050f968)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__se_sys_io_uring_enter
```
```
In fs/ext4/dir.c (c00000000057ed34)
Location: include/linux/compat.h:927
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
Location: include/linux/compat.h:927
Inline: True
```
```
In drivers/input/input-compat.c (c000000000b793cc)
Location: include/linux/compat.h:927
Inline: True
```
```
In drivers/input/evdev.c (c000000000b7f008)
Location: include/linux/compat.h:927
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
Location: include/linux/compat.h:927
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
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_set_timeout
```
```
In net/xfrm/xfrm_state.c (c000000000e058f8)
Location: include/linux/compat.h:927
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In kernel/time/time.c (0)
Location: include/linux/compat.h:964
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/compat.h:964
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/compat.h:964
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/compat.h:964
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/compat.h:964
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
In kernel/ptrace.c (ffffffff810a7c2a)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b07c5)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user_any
```
```
In kernel/time/time.c (ffffffff8112b2d5)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff8117660b)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8118a441)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In fs/io_uring.c (ffffffff8133d235)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff81388393)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In drivers/input/input.c (ffffffff8180c275)
Location: arch/x86/include/asm/compat.h:226
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8180e89c)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81811d24)
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
In drivers/input/misc/uinput.c (ffffffff81815fdc)
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
In drivers/firmware/efi/efivars.c (ffffffff8188d0bb)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff818b1af9)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff819c4a24)
Location: arch/x86/include/asm/compat.h:226
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
In kernel/ptrace.c (ffffffff81096604)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8109f0e5)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user_any
```
```
In kernel/time/time.c (ffffffff8111db45)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff811697ab)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8117d571)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In fs/io_uring.c (ffffffff8132def5)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff81378e23)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In drivers/input/input.c (ffffffff817d39e5)
Location: arch/x86/include/asm/compat.h:226
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff817d5fec)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff817d945e)
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
In drivers/input/misc/uinput.c (ffffffff817dd6dc)
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
In drivers/firmware/efi/efivars.c (ffffffff81844a3b)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff8186ba49)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff81981814)
Location: arch/x86/include/asm/compat.h:226
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
In kernel/ptrace.c (ffffffff810a718a)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810afd25)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user_any
```
```
In kernel/time/time.c (ffffffff81128ff5)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff811743db)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81188211)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In fs/io_uring.c (ffffffff8133ad05)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff81385cf3)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In drivers/input/input.c (ffffffff8184b3f5)
Location: arch/x86/include/asm/compat.h:226
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8184da1c)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81850ea4)
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
In drivers/input/misc/uinput.c (ffffffff818574bc)
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
In drivers/firmware/efi/efivars.c (ffffffff818df19b)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff81902af9)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f4a4)
Location: arch/x86/include/asm/compat.h:226
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
In kernel/ptrace.c (ffffffff810af4f5)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b7ff5)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user_any
```
```
In kernel/time/time.c (ffffffff81135645)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff81181cbb)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81195b71)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
```
```
In fs/io_uring.c (ffffffff8134deb5)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/ext4/dir.c (ffffffff813999e3)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In drivers/input/input.c (ffffffff81866655)
Location: arch/x86/include/asm/compat.h:226
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff81868bec)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8186c92b)
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
In drivers/input/misc/uinput.c (ffffffff818725dc)
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
In drivers/firmware/efi/efivars.c (ffffffff818fbc3b)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/core/sock.c (ffffffff81923a99)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3adf4)
Location: arch/x86/include/asm/compat.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
</details>
</li>
</ul>

## Differences
