# Function: <code>in_ia32_syscall</code>

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
In arch/x86/entry/common.c (ffffffff81003308)
Location: arch/x86/include/asm/thread_info.h:272
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vdso/vma.c (ffffffff8100428b)
Location: arch/x86/include/asm/thread_info.h:272
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/kernel/process_64.c (ffffffff8102ce78)
Location: arch/x86/include/asm/thread_info.h:272
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103cbd0)
Location: arch/x86/include/asm/thread_info.h:272
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
```
In arch/x86/kernel/uprobes.c (ffffffff81065db3)
Location: arch/x86/include/asm/thread_info.h:272
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
```
In kernel/ptrace.c (ffffffff8108e2c6)
Location: arch/x86/include/asm/thread_info.h:272
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/auditsc.c (ffffffff81131abb)
Location: arch/x86/include/asm/thread_info.h:272
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81144487)
Location: arch/x86/include/asm/thread_info.h:272
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116c56e)
Location: arch/x86/include/asm/thread_info.h:272
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In fs/ext4/dir.c (ffffffff812be054)
Location: arch/x86/include/asm/thread_info.h:272
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
Location: arch/x86/include/asm/thread_info.h:272
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff816ca38c)
Location: arch/x86/include/asm/thread_info.h:272
Inline: True
```
```
In drivers/input/evdev.c (ffffffff816cdc9d)
Location: arch/x86/include/asm/thread_info.h:272
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
Location: arch/x86/include/asm/thread_info.h:272
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
Location: arch/x86/include/asm/thread_info.h:272
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
