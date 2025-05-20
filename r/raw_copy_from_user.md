# Function: <code>raw_copy_from_user</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810076b8)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8102bf08)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81037c1f)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81037d75)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038e37)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
```
```
In arch/x86/kernel/tls.c (ffffffff8103b2a4)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103bf2c)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107be46)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/trace/trace.c (ffffffff811619dc)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff81182fe8)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In mm/maccess.c (ffffffff811be00b)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff811f24a0)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff81464eb4)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffff8146c5f7)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffffffff81664728)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
```
```
In arch/x86/lib/usercopy.c (ffffffff818fd4d5)
Location: arch/x86/include/asm/uaccess_64.h:49
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81007aee)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8102cc25)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81039ecf)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a025)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b377)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff8103dcd4)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103eb20)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81082542)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/trace/trace.c (ffffffff8116e25c)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff81190c4d)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In mm/maccess.c (ffffffff811d2ccc)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff81209464)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff81490e31)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffff81498917)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffffffff816cdd78)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
```
```
In arch/x86/lib/usercopy.c (ffffffff81984fb5)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81008127)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8102de55)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103abda)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b537)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c894)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff8103f26a)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81040101)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81085c02)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/trace/trace.c (ffffffff8117d26c)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a6182)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In mm/maccess.c (ffffffff811f404c)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8122a372)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff814c6215)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffff814cdb67)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffffffff8170781c)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff819e14a4)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81008007)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8102f095)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103c0da)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ca5c)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ddb4)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff8104086a)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810416c1)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108c972)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/trace/trace.c (ffffffff8118aadc)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812063dc)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8123d9b6)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff814da975)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffff814e2437)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffffffff8172a376)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1c454)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81008301)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user32
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/kernel/signal.c (ffffffff81030e64)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ee84)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f0ab)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810405ca)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81042f19)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81043bc6)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090842)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/trace/trace.c (ffffffff8119872a)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8121d89d)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8124f660)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff81506171)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffff8150e2f7)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffffffff81765a12)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff81a8c103)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81008519)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff81031724)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f594)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f714)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040d9a)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81043679)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81044316)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81091482)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/trace/trace.c (ffffffff811a401a)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8122b33d)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8125dbef)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff815241a1)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffff8152c147)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffffffff81789a02)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff81ac33c3)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/kernel/fpu/regset.c (ffffffff81042744)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042a44)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043ff0)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81046f03)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff811bd44a)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff81257fed)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff8128d2fd)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff8158975d)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
```
```
In lib/usercopy.c (ffffffff8158fb9c)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff815ff906)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/kernel/fpu/regset.c (ffffffff81042714)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104298b)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043e71)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81046753)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff811bb05a)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8126293f)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff812982df)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff815a4368)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffff815ac707)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff816236a5)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff81624836)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/kernel/fpu/regset.c (ffffffff810440f4)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104436c)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045b71)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81048169)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff811be842)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812672db)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff8129d92f)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff815ad95a)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
```
```
In lib/usercopy.c (ffffffff815b7386)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff81606f55)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff81608226)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/kernel/fpu/regset.c (ffffffff8104a496)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a807)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
```
In arch/x86/kernel/tls.c (ffffffff8104ea79)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff811e90f6)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812a3d1b)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff812ddfc4)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff81614e9f)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:_copy_from_iter
```
```
In lib/usercopy.c (ffffffff8161d9b6)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff81675a68)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff81676e66)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/kernel/fpu/regset.c (ffffffff81054658)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054cae)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
```
In arch/x86/kernel/tls.c (ffffffff81059c73)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff81220dc1)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812fbc54)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff8133e054)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff816e2de0)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:_copy_from_iter
```
```
In lib/usercopy.c (ffffffff816eb547)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff817906e8)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff81791e0b)
Location: arch/x86/include/asm/uaccess_64.h:50
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
In arch/x86/kernel/fpu/regset.c (ffffffff81062268)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106280e)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
```
In arch/x86/kernel/tls.c (ffffffff81067623)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff8126bc61)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff81365e24)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff813b7170)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff817d55e5)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
```
```
In lib/usercopy.c (ffffffff817dbc1a)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff8204e2f8)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff8204fc2e)
Location: arch/x86/include/asm/uaccess_64.h:50
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
In arch/x86/kernel/fpu/regset.c (ffffffff810632eb)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106436c)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/tls.c (ffffffff81068eb5)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff81282fc1)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff813982c6)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff813e98fb)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
```
```
In lib/iov_iter.c (ffffffff81810229)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffff8181af85)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff820ccb8f)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff820ce156)
Location: arch/x86/include/asm/uaccess_64.h:125
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
In arch/x86/kernel/fpu/regset.c (ffffffff8106a5eb)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b842)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/tls.c (ffffffff8107032b)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff8129e351)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff813c20f6)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff814148f1)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
```
```
In lib/iov_iter.c (ffffffff8185837f)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
```
```
In lib/usercopy.c (ffffffff818602e4)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff821a73bf)
Location: arch/x86/include/asm/uaccess_64.h:125
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff821a8986)
Location: arch/x86/include/asm/uaccess_64.h:125
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ptrace.c (c030cb34)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:vfp_set
  - arch/arm/kernel/ptrace.c:vfp_set
  - arch/arm/kernel/ptrace.c:fpa_set
  - arch/arm/kernel/ptrace.c:gpr_set
```
```
In arch/arm/kernel/signal.c (c030e1c4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:restore_sigframe
  - arch/arm/kernel/signal.c:restore_sigframe
  - arch/arm/kernel/signal.c:restore_vfp_context
  - arch/arm/kernel/signal.c:restore_iwmmxt_context
```
```
In arch/arm/kernel/perf_callchain.c (c0317ce4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - arch/arm/kernel/perf_callchain.c:perf_callchain_user
```
```
In kernel/fork.c (c03508c4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sysctl_binary.c (c0360974)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__se_sys_sysctl
```
```
In kernel/capability.c (c03612b0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
```
```
In kernel/ptrace.c (c0363180)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_writedata
```
```
In kernel/signal.c (c036a924)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigsuspend
  - kernel/signal.c:__se_sys_rt_sigaction
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:__se_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
  - kernel/signal.c:__se_sys_rt_sigprocmask
  - kernel/signal.c:set_user_sigmask
```
```
In kernel/sys.c (c036b268)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__se_sys_setrlimit
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_setdomainname
  - kernel/sys.c:__se_sys_sethostname
```
```
In kernel/sched/core.c (c038cb6c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
```
```
In kernel/sched/debug.c (c03ac394)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/sched/psi.c (c03b4ad0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
```
```
In kernel/power/qos.c (c03b8834)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_write
```
```
In kernel/power/user.c (c03c3b08)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In kernel/kcmp.c (c03e2d6c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/profile.c (c03e3dd4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
```
```
In kernel/time/time.c (c03e5148)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/time/time.c:get_old_itimerspec32
  - kernel/time/time.c:get_old_itimerspec32
  - kernel/time/time.c:get_old_timespec32
  - kernel/time/time.c:get_timespec64
  - kernel/time/time.c:get_old_timex32
  - kernel/time/time.c:__se_sys_settimeofday
  - kernel/time/time.c:__se_sys_settimeofday
```
```
In kernel/time/posix-timers.c (c03f74b0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__se_sys_timer_create
```
```
In kernel/time/itimer.c (c03fad50)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/time/itimer.c:__se_sys_setitimer
```
```
In kernel/module.c (c040cbe4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/module.c:__se_sys_init_module
```
```
In kernel/kexec_core.c (c041060c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In kernel/kexec.c (c0410f44)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/user_namespace.c (c04273b4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_setgroups_write
```
```
In kernel/kprobes.c (c0438950)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
```
```
In kernel/seccomp.c (c04492dc)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In kernel/trace/trace.c (c0467cdc)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:tracing_trace_options_write
```
```
In kernel/trace/blktrace.c (c0471d5c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
```
```
In kernel/trace/bpf_trace.c (c0481990)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_uprobe.c (c048d238)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/bpf/syscall.c (c0497070)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (c049b908)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (c04b626c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/cgroup.c (c04bd464)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (c04c5474)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/rseq.c (c04d9580)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
```
```
In mm/maccess.c (c04e5bec)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/shmem.c (c04fb410)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/util.c (c04ffb3c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - mm/util.c:memdup_user_nul
  - mm/util.c:vmemdup_user
  - mm/util.c:memdup_user
```
```
In mm/memory.c (c05172f4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (c051fb64)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_old_mmap
```
```
In mm/userfaultfd.c (c0563d34)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/memfd.c (c056700c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - mm/memfd.c:__se_sys_memfd_create
```
```
In fs/read_write.c (c056ddb8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/exec.c (c05749f0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
```
```
In fs/fcntl.c (c05823b4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (c05838b0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:ioctl_preallocate
```
```
In fs/select.c (c05858b0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:__se_sys_old_select
  - fs/select.c:kern_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/xattr.c (c059bd28)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/xattr.c:setxattr
```
```
In fs/libfs.c (c059e634)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_write_to_buffer
```
```
In fs/splice.c (c05aa168)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/notify/fanotify/fanotify_user.c (c05c4bd8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (c05c79c0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
```
```
In fs/signalfd.c (c05c90b0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/signalfd.c:__se_sys_signalfd
  - fs/signalfd.c:__se_sys_signalfd4
```
```
In fs/timerfd.c (c05c988c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_ioctl
```
```
In fs/eventfd.c (c05cadb8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
```
```
In fs/userfaultfd.c (c05cc8ac)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
```
```
In fs/aio.c (c05d1a90)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_submit
```
```
In fs/io_uring.c (c05d7848)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_uring_setup
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/crypto/keyring.c (c05dae18)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (c05dcfd8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (c05de010)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/binfmt_elf.c (c05e6338)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_psinfo
```
```
In fs/binfmt_elf_fdpic.c (c05e95bc)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:fill_psinfo
```
```
In fs/fhandle.c (c05f2184)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:do_sys_name_to_handle
```
```
In fs/quota/quota.c (c05fe7c4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_setquota
```
```
In fs/proc/task_mmu.c (c0600104)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (c0605a50)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - fs/proc/base.c:mem_rw
```
```
In fs/kernfs/file.c (c0617b10)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_write
```
```
In fs/configfs/file.c (c061ad8c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_write_file
```
```
In fs/ext4/ioctl.c (c064daa8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
```
```
In fs/fat/file.c (c06a914c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/miscdev.c (c06bb0f0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
```
```
In fs/pstore/ram_core.c (c06d74dc)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/pstore/ram_core.c:persistent_ram_update_user
```
```
In fs/efivarfs/file.c (c06d8554)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In ipc/msgutil.c (c06da7b8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
```
```
In ipc/msg.c (c06dbd08)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - ipc/msg.c:copy_msqid_from_user
  - ipc/msg.c:copy_msqid_from_user
```
```
In ipc/sem.c (c06dee94)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:copy_semid_from_user
  - ipc/sem.c:copy_semid_from_user
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (c06e1034)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
```
In ipc/mqueue.c (c06e4e68)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:__se_sys_mq_open
```
```
In security/keys/keyctl.c (c06e9c80)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/keys/dh.c (c06ef618)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/keyctl_pkey.c (c06ef8a4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
```
In security/selinux/selinuxfs.c (c070b96c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
```
In security/smack/smackfs.c (c072961c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
```
```
In security/apparmor/apparmorfs.c (c073dd04)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In block/ioctl.c (c07a39b8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_pr_preempt
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/scsi_ioctl.c (c07b4874)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (c07b4d80)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
```
```
In block/blk-zoned.c (c07c7f34)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In block/blk-mq-debugfs.c (c07cad4c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In block/sed-opal.c (c07cea44)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
```
In lib/iov_iter.c (c07d6414)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:copyin
```
```
In lib/kfifo.c (c07dab10)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - lib/kfifo.c:kfifo_copy_from_user
  - lib/kfifo.c:kfifo_copy_from_user
```
```
In lib/kstrtox.c (c07e064c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtou8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtou16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtobool_from_user
```
```
In drivers/gpio/gpiolib.c (c0861498)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (c08c8ca8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
```
```
In drivers/video/fbdev/core/fbcmap.c (c08cbd2c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbcon.c (c08d5908)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
```
```
In drivers/video/fbdev/imsttfb.c (c08dd66c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
```
```
In drivers/tty/tty_io.c (c095cfa0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/tty_ioctl.c (c0963a24)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
```
```
In drivers/tty/vt/vt_ioctl.c (c096bdb4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
```
```
In drivers/tty/vt/vc_screen.c (c096cedc)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
```
```
In drivers/tty/vt/selection.c (c096e7f8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection_user
  - drivers/tty/vt/selection.c:sel_loadlut
```
```
In drivers/tty/vt/keyboard.c (c097224c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
```
```
In drivers/tty/vt/consolemap.c (c0973980)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_old
```
```
In drivers/tty/vt/vt.c (c097914c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_set_cmap
```
```
In drivers/tty/serial/serial_core.c (c0982314)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/mem.c (c09a76ec)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
```
```
In drivers/char/random.c (c09a9ac8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
```
```
In drivers/char/virtio_console.c (c09afd8c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (c09b2370)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
```
```
In drivers/lightnvm/core.c (c09d0124)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
```
In drivers/block/loop.c (c0a07ea0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
```
In drivers/mfd/ab3100-core.c (c0a32e74)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
```
```
In drivers/mfd/aat2870-core.c (c0a3671c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/dma-buf/dma-buf.c (c0a3c044)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
```
In drivers/dma-buf/sync_file.c (c0a409f4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/dma-buf/sw_sync.c (c0a412d0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/udmabuf.c (c0a42544)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
```
In drivers/scsi/scsi_devinfo.c (c0a533a8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
```
```
In drivers/scsi/scsi_proc.c (c0a53f3c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
```
```
In drivers/scsi/sg.c (c0a642a0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_new_write
  - drivers/scsi/sg.c:sg_new_write
```
```
In drivers/ata/libata-scsi.c (c0a752cc)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
```
In drivers/gpu/vga/vgaarb.c (c0a8d908)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
```
```
In drivers/mtd/mtdchar.c (c0a96b3c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_write
```
```
In drivers/net/tun.c (c0ac62d8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0aced24)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad400c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (c0adfa80)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/cdrom/cdrom.c (c0ae7214)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_play_blk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_play_msf
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
```
```
In drivers/usb/core/devio.c (c0b05690)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
```
In drivers/usb/host/xhci-debugfs.c (c0b61f20)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/usb/musb/musb_debugfs.c (c0b71514)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_write
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_write
```
```
In drivers/input/input-compat.c (c0b7b410)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (c0b7f6e8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_handle_set_keycode_v2
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:evdev_handle_get_keycode
```
```
In drivers/input/misc/uinput.c (c0b84580)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ff_upload_from_user
  - drivers/input/misc/uinput.c:uinput_dev_setup
```
```
In drivers/rtc/dev.c (c0b895c8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
```
In drivers/i2c/i2c-dev.c (c0b97da0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
```
In drivers/media/cec/cec-api.c (c0ba41d4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
```
```
In drivers/pps/pps.c (c0ba587c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
```
```
In drivers/ptp/ptp_chardev.c (c0ba74ec)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In drivers/md/md.c (c0bd568c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (c0be79cc)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In drivers/mmc/core/block.c (c0c1b7a0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
```
```
In drivers/firmware/tegra/bpmp-debugfs.c (c0c42a2c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
```
```
In drivers/remoteproc/remoteproc_debugfs.c (c0c65b80)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
```
In sound/core/memory.c (c0c84c10)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - sound/core/memory.c:copy_from_user_toio
```
```
In sound/core/control.c (c0c87bb8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_tlv_ioctl
  - sound/core/control.c:snd_ctl_elem_add_user
  - sound/core/control.c:snd_ctl_elem_info_user
  - sound/core/control.c:snd_ctl_elem_list
```
```
In sound/core/info.c (c0c89768)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - sound/core/info.c:snd_info_text_entry_write
```
```
In sound/core/timer.c (c0c8e738)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
```
```
In sound/core/pcm_native.c (c0c9549c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_sw_params_user
```
```
In sound/core/pcm_lib.c (c0c990e8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:default_write_copy
```
```
In sound/core/compress_offload.c (c0c9e858)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_write
  - sound/core/compress_offload.c:snd_compr_write
  - sound/core/compress_offload.c:snd_compr_write
```
```
In sound/soc/soc-generic-dmaengine-pcm.c (c0cbb654)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - sound/soc/soc-generic-dmaengine-pcm.c:dmaengine_copy_user
```
```
In net/socket.c (c0cc4e8c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:move_addr_to_kernel
```
```
In net/core/sock.c (c0ccc04c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
```
```
In net/core/ethtool.c (c0cf6e80)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_set_per_queue
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_flash_device
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_copy_validate_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:load_link_ksettings_from_user
```
```
In net/core/filter.c (c0d1b73c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
```
In net/core/dev_ioctl.c (c0d1d360)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/bpf/test_run.c (c0d63730)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_test_init
```
```
In net/ipv4/ip_options.c (c0d7118c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get_from_user
```
```
In net/ipv4/ip_sockglue.c (c0d760a8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
```
```
In net/ipv4/tcp.c (c0d8071c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c0d9bb8c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
```
```
In net/ipv4/raw.c (c0da54d8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
```
```
In net/ipv4/arp.c (c0dafe68)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
```
```
In net/ipv4/af_inet.c (c0db8bb4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
```
In net/ipv4/fib_frontend.c (c0dbf634)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/ipmr.c (c0dd9d78)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/ipv6/addrconf.c (c0e0fec8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
```
In net/ipv6/route.c (c0e1c77c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
```
In net/ipv6/ipv6_sockglue.c (c0e21b44)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
```
```
In net/ipv6/raw.c (c0e2d2b4)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c0e39bec)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/ip6_flowlabel.c (c0e4285c)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (c0e49444)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (c0e5d4bc)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/wireless/wext-core.c (c0e60eb0)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
```
```
In net/wireless/wext-priv.c (c0e61884)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:ioctl_private_iw_point
```
```
In net/rfkill/core.c (c0e6a430)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_write
```
```
In net/xdp/xsk.c (c0e7a5e8)
Location: arch/arm/include/asm/uaccess.h:516
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
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
In arch/powerpc/kernel/ptrace.c (c0000000000160b8)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:pmu_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:tar_set
  - arch/powerpc/kernel/ptrace.c:dscr_set
  - arch/powerpc/kernel/ptrace.c:ppr_set
  - arch/powerpc/kernel/ptrace.c:tm_dscr_set
  - arch/powerpc/kernel/ptrace.c:tm_ppr_set
  - arch/powerpc/kernel/ptrace.c:tm_tar_set
  - arch/powerpc/kernel/ptrace.c:tm_spr_set
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:vr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
```
```
In arch/powerpc/kernel/signal_32.c (c00000000001d020)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:copy_ckvsx_from_user
  - arch/powerpc/kernel/signal_32.c:copy_ckfpr_from_user
  - arch/powerpc/kernel/signal_32.c:copy_vsx_from_user
  - arch/powerpc/kernel/signal_32.c:copy_fpr_from_user
```
```
In arch/powerpc/kernel/traps.c (c00000000002cd40)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:p9_hmi_special_emu
```
```
In arch/powerpc/kernel/signal_64.c (c000000000033fb8)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009fdc0)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
```
```
In arch/powerpc/lib/pmem.c (c0000000000a7f88)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - arch/powerpc/lib/pmem.c:__copy_from_user_flushcache
```
```
In arch/powerpc/lib/checksum_wrappers.c (c0000000000aa0a4)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
```
```
In kernel/trace/trace.c (c0000000002a72ec)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/events/core.c (c00000000034284c)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In mm/maccess.c (c000000000371968)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (c0000000003bc144)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (c0000000007d8354)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (c0000000007de2e0)
Location: arch/powerpc/include/asm/uaccess.h:323
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/scsi/sg.c (c000000000a533f8)
Location: arch/powerpc/include/asm/uaccess.h:323
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
In arch/riscv/kernel/ptrace.c (ffffffe0000b623c)
Location: arch/riscv/include/asm/uaccess.h:376
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:riscv_fpr_set
  - arch/riscv/kernel/ptrace.c:riscv_fpr_set
  - arch/riscv/kernel/ptrace.c:riscv_gpr_set
```
```
In arch/riscv/kernel/signal.c (ffffffe0000b68c4)
Location: arch/riscv/include/asm/uaccess.h:376
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/riscv/kernel/perf_callchain.c (ffffffe0000b98d4)
Location: arch/riscv/include/asm/uaccess.h:376
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_callchain.c:user_backtrace
```
```
In kernel/trace/trace.c (ffffffe00017d668)
Location: arch/riscv/include/asm/uaccess.h:376
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/events/core.c (ffffffe0001ce9c4)
Location: arch/riscv/include/asm/uaccess.h:376
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/maccess.c (ffffffe0001dd02e)
Location: arch/riscv/include/asm/uaccess.h:376
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffe00020651c)
Location: arch/riscv/include/asm/uaccess.h:376
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffe00045ede8)
Location: arch/riscv/include/asm/uaccess.h:376
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffe000464f3c)
Location: arch/riscv/include/asm/uaccess.h:376
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In lib/checksum.c (ffffffe00048ec10)
Location: arch/riscv/include/asm/uaccess.h:376
Inline: True
Inline callers:
  - lib/checksum.c:csum_partial_copy_from_user
```
```
In drivers/scsi/sg.c (ffffffe0005f4992)
Location: arch/riscv/include/asm/uaccess.h:376
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
In arch/x86/events/core.c (ffffffff81008519)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff81031884)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f714)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f894)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040f1a)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff810437f9)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81044496)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090442)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/trace/trace.c (ffffffff8119c63a)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8122398d)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8125623f)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff8151c781)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffff81524727)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffffffff8173e0f2)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff81a62213)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81006d09)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff81021264)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8102ef14)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f094)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810306fa)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81032e19)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81033ab6)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107ef52)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/trace/trace.c (ffffffff8118f6b4)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff81216b3d)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff812488d8)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff8150ca71)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffff81514a07)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffffffff8171fd92)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1f283)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff810084d9)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff810316e4)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f554)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f6d4)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040d5a)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81043639)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810442d6)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810903f2)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/trace/trace.c (ffffffff8119a40a)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8122172d)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff81253fdf)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff81518811)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffff815207b7)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffffffff8177e882)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff81ace603)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81008639)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff81032594)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81040834)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810409c4)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104213a)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81044a39)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810456d6)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810927d2)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/trace/trace.c (ffffffff811a80aa)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812308ed)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff81263a34)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffff81531fd1)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (ffffffff8153a137)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffffffff81798688)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff81adab13)
Location: arch/x86/include/asm/uaccess_64.h:66
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
</details>
</li>
</ul>

## Differences
