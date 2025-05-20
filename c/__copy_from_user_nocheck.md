# Function: <code>__copy_from_user_nocheck</code>

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
In arch/x86/kernel/signal.c (ffffffff8102ed0f)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack_64.c (ffffffff81031796)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack_64.c:is_valid_bugaddr
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a5c2)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ad10)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/tls.c (ffffffff8103db16)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e707)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810782c5)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
```
```
In kernel/futex.c (ffffffff8110018a)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
```
```
In kernel/trace/trace_kprobe.c (ffffffff811674bb)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff81188d4d)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff8119153b)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (ffffffff811bc8e9)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
```
```
In fs/compat_ioctl.c (ffffffff812666b1)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In block/compat_ioctl.c (ffffffff813e592c)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In arch/x86/lib/usercopy.c (ffffffff813f78ee)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
```
```
In lib/iov_iter.c (ffffffff813fb981)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff815c39c8)
Location: arch/x86/include/asm/uaccess_64.h:52
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
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
In arch/x86/events/core.c (ffffffff810078a2)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8102de28)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack_64.c (ffffffff810308a9)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack_64.c:is_valid_bugaddr
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a410)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a56b)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b6cb)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
```
```
In arch/x86/kernel/tls.c (ffffffff8103d946)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e54f)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81079866)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/trace/trace_kprobe.c (ffffffff81174a72)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In mm/maccess.c (ffffffff811a5d05)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff811d7657)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In block/compat_ioctl.c (ffffffff8142bc1b)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In arch/x86/lib/usercopy.c (ffffffff8143e77f)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
```
```
In lib/iov_iter.c (ffffffff81444694)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff8161f33a)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
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
In arch/x86/events/core.c (ffffffff81007928)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8102dc88)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack_64.c (ffffffff81030509)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack_64.c:is_valid_bugaddr
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81039d00)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81039e5a)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103af6b)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
```
```
In arch/x86/kernel/tls.c (ffffffff8103d236)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103deaf)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d656)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/trace/trace.c (ffffffff8115e79b)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff811804f2)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In mm/maccess.c (ffffffff811b6085)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff811e735e)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/pstore/platform.c (ffffffff8136ba73)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_write_buf_user_compat
```
```
In block/compat_ioctl.c (ffffffff81445a1b)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In arch/x86/lib/usercopy.c (ffffffff8145b7f6)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:_copy_from_user
```
```
In lib/iov_iter.c (ffffffff8146280d)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_from_iter_full
  - lib/iov_iter.c:copy_from_iter_full
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff8164fea8)
Location: arch/x86/include/asm/uaccess_64.h:53
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
```
</details>
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
