# Function: <code>force_sig</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f100)
Location: kernel/signal.c:1435
Inline: True
Inline callers:
  - kernel/signal.c:force_sigsegv
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - kernel/pid_namespace.c:reboot_pid_ns
  - mm/memory-failure.c:memory_failure
  - drivers/tty/tty_io.c:__do_SAK
```
**Symbols:**

```
ffffffff8108f100-ffffffff8108f118: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092cc2)
Location: kernel/signal.c:1435
Inline: True
Inline callers:
  - kernel/signal.c:force_sigsegv
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - kernel/pid_namespace.c:reboot_pid_ns
  - mm/memory-failure.c:memory_failure
  - drivers/tty/tty_io.c:__do_SAK
```
**Symbols:**

```
ffffffff81092170-ffffffff81092188: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097c52)
Location: kernel/signal.c:1441
Inline: True
Inline callers:
  - kernel/signal.c:force_sigsegv
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - kernel/pid_namespace.c:reboot_pid_ns
  - mm/memory-failure.c:memory_failure
  - drivers/tty/tty_io.c:__do_SAK
```
**Symbols:**

```
ffffffff81097100-ffffffff81097118: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094f62)
Location: kernel/signal.c:1463
Inline: True
Inline callers:
  - kernel/signal.c:force_sigsegv
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - kernel/pid_namespace.c:reboot_pid_ns
```
**Symbols:**

```
ffffffff81094400-ffffffff81094418: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109be02)
Location: kernel/signal.c:1464
Inline: True
Inline callers:
  - kernel/signal.c:force_sigsegv
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - kernel/pid_namespace.c:reboot_pid_ns
```
**Symbols:**

```
ffffffff8109b2a0-ffffffff8109b2b8: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109fe72)
Location: kernel/signal.c:1462
Inline: True
Inline callers:
  - kernel/signal.c:force_sigsegv
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - kernel/pid_namespace.c:reboot_pid_ns
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff8109f210-ffffffff8109f228: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a81e2)
Location: kernel/signal.c:1549
Inline: True
Inline callers:
  - kernel/signal.c:force_sigsegv
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff810a74d0-ffffffff810a74e8: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae3b0)
Location: kernel/signal.c:1618
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:force_sigsegv
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff810ae3b0-ffffffff810ae42d: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b49c0)
Location: kernel/signal.c:1623
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:force_sigsegv
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff810b49c0-ffffffff810b4a3d: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bdaeb)
Location: kernel/signal.c:1619
Inline: True
Inline callers:
  - kernel/signal.c:force_sigsegv
Direct callers:
  - arch/x86/entry/common.c:__prepare_exit_to_usermode
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_trampoline
```
**Symbols:**

```
ffffffff810bd7a0-ffffffff810bd800: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8dfb)
Location: kernel/signal.c:1620
Inline: True
Inline callers:
  - kernel/signal.c:force_sigsegv
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_trampoline
```
**Symbols:**

```
ffffffff810b8ab0-ffffffff810b8b10: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba3eb)
Location: kernel/signal.c:1622
Inline: True
Inline callers:
  - kernel/signal.c:force_sigsegv
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff810ba030-ffffffff810ba090: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ccc4b)
Location: kernel/signal.c:1648
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/tlb.c:l1d_flush_force_sigbus
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff810ccb40-ffffffff810ccba2: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e46d6)
Location: kernel/signal.c:1649
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:gp_user_force_sig_segv
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/tlb.c:l1d_flush_force_sigbus
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
```
**Symbols:**

```
ffffffff810e3e70-ffffffff810e3eec: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81104d46)
Location: kernel/signal.c:1650
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/tlb.c:l1d_flush_force_sigbus
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
```
**Symbols:**

```
ffffffff811044c0-ffffffff8110453c: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81110fc6)
Location: kernel/signal.c:1656
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/tlb.c:l1d_flush_force_sigbus
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
```
**Symbols:**

```
ffffffff81110740-ffffffff811107bc: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111a936)
Location: kernel/signal.c:1662
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/tlb.c:l1d_flush_force_sigbus
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
```
**Symbols:**

```
ffffffff8111a090-ffffffff8111a10c: force_sig (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110a70)
Location: kernel/signal.c:1623
Inline: False
Direct callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:force_sigsegv
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffff800010110a70-ffff800010110ae0: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0368228)
Location: kernel/signal.c:1623
Inline: False
Direct callers:
  - arch/arm/kernel/signal.c:addr_limit_check_failed
  - arch/arm/kernel/signal.c:sys_rt_sigreturn
  - arch/arm/kernel/signal.c:sys_sigreturn
  - kernel/signal.c:force_sigsegv
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
c0368228-c03682bc: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000158320)
Location: kernel/signal.c:1623
Inline: False
Direct callers:
  - arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal.c:do_notify_resume
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:force_sigsegv
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
c000000000158320-c0000000001583ac: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d068a)
Location: kernel/signal.c:1623
Inline: False
Direct callers:
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
  - kernel/signal.c:force_sigsegv
```
**Symbols:**

```
ffffffe0000d068a-ffffffe0000d06dc: force_sig (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aed30)
Location: kernel/signal.c:1623
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:force_sigsegv
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff810aed30-ffffffff810aedad: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d680)
Location: kernel/signal.c:1623
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:force_sigsegv
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff8109d680-ffffffff8109d6fd: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae290)
Location: kernel/signal.c:1623
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:force_sigsegv
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff810ae290-ffffffff810ae30d: force_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void force_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6500)
Location: kernel/signal.c:1623
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:force_sigsegv
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff810b6500-ffffffff810b657d: force_sig (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *p</code>
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
