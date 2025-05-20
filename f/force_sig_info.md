# Function: <code>force_sig_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int force_sig_info(int sig, struct siginfo *info, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f020)
Location: kernel/signal.c:1160
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/ptrace.c:send_sigtrap
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/fault.c:force_sig_info_fault
  - kernel/signal.c:force_sigsegv
  - kernel/seccomp.c:seccomp_send_sigsys
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff8108f020-ffffffff8108f0f7: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int force_sig_info(int sig, struct siginfo *info, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092090)
Location: kernel/signal.c:1160
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:send_sigtrap
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/fault.c:force_sig_info_fault
  - kernel/signal.c:force_sigsegv
  - kernel/seccomp.c:seccomp_send_sigsys
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81092090-ffffffff81092167: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int force_sig_info(int sig, struct siginfo *info, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097020)
Location: kernel/signal.c:1166
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:send_sigtrap
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/fault.c:force_sig_info_fault
  - kernel/signal.c:force_sigsegv
  - kernel/seccomp.c:seccomp_send_sigsys
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81097020-ffffffff810970f7: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int force_sig_info(int sig, struct siginfo *info, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094320)
Location: kernel/signal.c:1180
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:send_sigtrap
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/fault.c:force_sig_info_fault
  - kernel/signal.c:force_sigsegv
  - kernel/seccomp.c:seccomp_send_sigsys
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81094320-ffffffff810943fe: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int force_sig_info(int sig, struct siginfo *info, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b1c0)
Location: kernel/signal.c:1181
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:send_sigtrap
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/umip.c:force_sig_info_umip_fault
  - arch/x86/mm/fault.c:force_sig_info_fault
  - kernel/signal.c:force_sigsegv
  - kernel/seccomp.c:seccomp_send_sigsys
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff8109b1c0-ffffffff8109b29e: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int force_sig_info(int sig, struct siginfo *info, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f130)
Location: kernel/signal.c:1189
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:send_sigtrap
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/umip.c:force_sig_info_umip_fault
  - arch/x86/mm/fault.c:force_sig_info_fault
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sigsegv
  - kernel/seccomp.c:seccomp_send_sigsys
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff8109f130-ffffffff8109f20e: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int force_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a73f0)
Location: kernel/signal.c:1272
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sigsegv
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810a73f0-ffffffff810a74ce: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae70e)
Location: kernel/signal.c:1334
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810ae390-ffffffff810ae3a9: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4d1e)
Location: kernel/signal.c:1339
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810b49a0-ffffffff810b49b9: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bd9ce)
Location: kernel/signal.c:1339
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sigsegv
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810bd780-ffffffff810bd799: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8cde)
Location: kernel/signal.c:1340
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sigsegv
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810b8a90-ffffffff810b8aa9: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba2ce)
Location: kernel/signal.c:1342
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_perf
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sigsegv
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810ba010-ffffffff810ba029: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ccc6f)
Location: kernel/signal.c:1353
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_perf
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff810cc670-ffffffff810cc68b: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e46ef)
Location: kernel/signal.c:1354
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff810e3920-ffffffff810e3945: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81104d5f)
Location: kernel/signal.c:1355
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff81103ed0-ffffffff81103ef5: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81110fdf)
Location: kernel/signal.c:1359
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff81110150-ffffffff81110175: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111a94f)
Location: kernel/signal.c:1360
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff81119aa0-ffffffff81119ac5: force_sig_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110e84)
Location: kernel/signal.c:1339
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffff800010110a40-ffff800010110a70: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0368698)
Location: kernel/signal.c:1339
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
c03681fc-c0368228: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000158764)
Location: kernel/signal.c:1339
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
c000000000158300-c000000000158318: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d090c)
Location: kernel/signal.c:1339
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffe0000d065e-ffffffe0000d068a: force_sig_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af08e)
Location: kernel/signal.c:1339
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810aed10-ffffffff810aed29: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d9de)
Location: kernel/signal.c:1339
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8109d660-ffffffff8109d679: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae5ee)
Location: kernel/signal.c:1339
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810ae270-ffffffff810ae289: force_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int force_sig_info(struct kernel_siginfo *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b685e)
Location: kernel/signal.c:1339
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810b64e0-ffffffff810b64f9: force_sig_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct siginfo *info</code> ➡️ <code>struct kernel_siginfo *info</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int sig</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *t</code>
</li>
<li>
<b>Param reordered. </b>
<code>sig, info, t</code> ➡️ <code>info</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
