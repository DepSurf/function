# Function: <code>clear_ti_thread_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clear_ti_thread_flag(struct thread_info *ti, int flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810031b0)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff8102d01f)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff8102f273)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103902c)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:exit_thread
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103b893)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
  - arch/x86/kernel/ptrace.c:ptrace_disable
```
```
In arch/x86/kernel/step.c (ffffffff8103dc85)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81050138)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051a2b)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
```
In kernel/fork.c (ffffffff8107d640)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff81082741)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff8108b57a)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8108d192)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff8181faec)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810c3cee)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/pid_namespace.c (ffffffff8111fcfc)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81128262)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8113fd19)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff81188b10)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In kernel/user-return-notifier.c (ffffffff81189779)
Location: include/linux/thread_info.h:74
Inline: True
```
```
In mm/oom_kill.c (ffffffff81190a7e)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff8126f863)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff81479497)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle_freeze
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff8152373b)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815289cc)
Location: include/linux/thread_info.h:74
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff816bc0ad)
Location: include/linux/thread_info.h:74
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
**Symbols:**

```
ffffffff8107d640-ffffffff8107d64f: clear_ti_thread_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clear_ti_thread_flag(struct thread_info *ti, int flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810032a1)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c01f)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff8102e2ef)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103806e)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c8c2)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103dccd)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81050294)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051bbb)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
```
In kernel/fork.c (ffffffff8107f130)
Location: include/linux/thread_info.h:75
Inline: True
```
```
In kernel/exit.c (ffffffff8108577a)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff8108f091)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81090c72)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff8189a221)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810c7bf4)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/pid_namespace.c (ffffffff81127c50)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8113040c)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff81148379)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff8119b294)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8119be5b)
Location: include/linux/thread_info.h:75
Inline: True
```
```
In fs/coredump.c (ffffffff8129b52c)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff814c7940)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81576738)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157bf1c)
Location: include/linux/thread_info.h:75
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff8171d9bd)
Location: include/linux/thread_info.h:75
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
**Symbols:**

```
ffffffff8107f130-ffffffff8107f13f: clear_ti_thread_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clear_ti_thread_flag(struct thread_info *ti, int flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8100328b)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c01c)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff8102e247)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff818d3bcc)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c142)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103d597)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff818d3d24)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/fork.c (ffffffff810837e0)
Location: include/linux/thread_info.h:46
Inline: True
```
```
In kernel/exit.c (ffffffff8108a6fc)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81093116)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81095c05)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff818ce84a)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810cda3d)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/pid_namespace.c (ffffffff811318d9)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8113a17c)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff81152239)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff811aac94)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811ab83b)
Location: include/linux/thread_info.h:46
Inline: True
```
```
In mm/oom_kill.c (ffffffff811b597e)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff812b00eb)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff814e9861)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815a2e04)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a8399)
Location: include/linux/thread_info.h:46
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff818d406e)
Location: include/linux/thread_info.h:46
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
**Symbols:**

```
ffffffff810837e0-ffffffff810837ee: clear_ti_thread_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clear_ti_thread_flag(struct thread_info *ti, int flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003125)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff8102a1b1)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff8102c357)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8190ad39)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103a182)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103b5e7)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8190ae84)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/fork.c (ffffffff810806b0)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In kernel/exit.c (ffffffff81087767)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81090226)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81092bb5)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81905c71)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810ca453)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff810f931f)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/pid_namespace.c (ffffffff81132ea9)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8113b7bc)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff81154819)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff811b21b1)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811b2ca7)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In mm/oom_kill.c (ffffffff811bd6be)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff812bd5ba)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff814f5481)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815b6988)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815bd891)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
```
In drivers/cpuidle/driver.c (ffffffff8190b1f9)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
**Symbols:**

```
ffffffff810806b0-ffffffff810806be: clear_ti_thread_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clear_ti_thread_flag(struct thread_info *ti, int flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003dd5)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff8102af81)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff8102d257)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff819950ac)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103cb92)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103e007)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff819951f4)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/fork.c (ffffffff81086f50)
Location: include/linux/thread_info.h:62
Inline: True
```
```
In kernel/exit.c (ffffffff8108e4f7)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81097096)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81099a95)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff8198fced)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810d1c6e)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff81103d54)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_switch_task
```
```
In kernel/pid_namespace.c (ffffffff8113fc49)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8114851b)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff81161039)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff811c5dc1)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811c68f7)
Location: include/linux/thread_info.h:62
Inline: True
```
```
In mm/oom_kill.c (ffffffff811d2302)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff812e0e89)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff81535d01)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff8161d6b4)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81623d77)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
```
In drivers/cpuidle/poll_state.c (ffffffff81995593)
Location: include/linux/thread_info.h:62
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
**Symbols:**

```
ffffffff81086f50-ffffffff81086f5e: clear_ti_thread_flag (STB_LOCAL)
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
In arch/x86/entry/common.c (ffffffff81004572)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c18c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff8102e207)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff819f1613)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103e122)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103f5b7)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff819f1752)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/fork.c (ffffffff8108c2f3)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In kernel/exit.c (ffffffff81091f51)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In kernel/ptrace.c (ffffffff8109a58c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff8109da65)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff819ec539)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810c438c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff8110c1b4)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_switch_task
```
```
In kernel/pid_namespace.c (ffffffff8114e54a)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81156eeb)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8116ff88)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff811e62a1)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811e6e37)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In mm/oom_kill.c (ffffffff811f324f)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff8130d0bf)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff8156b8a2)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165de5c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff819f1ad3)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/entry/common.c (ffffffff810045a2)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff8102d23c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff8102f4c7)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81a2ca45)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103f702)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81040bb7)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2cbf2)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/fork.c (ffffffff81093d0d)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In kernel/exit.c (ffffffff8109a241)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In kernel/ptrace.c (ffffffff810a27cc)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810a5d75)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81a277bb)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810cd64c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff811179a4)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_switch_task
```
```
In kernel/pid_namespace.c (ffffffff8115b22f)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81163f3b)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8117db38)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff811f6df1)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811f7a67)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In mm/oom_kill.c (ffffffff8120523f)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff81322988)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff81583422)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167c31c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2d068)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/entry/common.c (ffffffff810047c5)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff8102f15c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff810312c7)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81a9cbac)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103de44)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f792)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff810418d0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81043297)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd60)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/fork.c (ffffffff8109843a)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109e860)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a7452)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810aefd3)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81a98057)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810d5a35)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff81121ddc)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/pid_namespace.c (ffffffff811678c8)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81170b49)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8118a9e1)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff8120f48f)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8120f8a5)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121cd3e)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff8134a3e9)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b6d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b326d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a9d1e8)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/entry/common.c (ffffffff81004825)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff8102fabc)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81031b87)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81ad43fc)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e604)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fec8)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042050)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810439f7)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad45b0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/fork.c (ffffffff8109ea14)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a4e05)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810ada76)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b55ea)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81acf92d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810e0045)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff8112e3fc)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/pid_namespace.c (ffffffff81173788)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8117c9c9)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff811968f1)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff8121cb3f)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8121ced5)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122a71e)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff81362689)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff815d4dad)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d5f4d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff81ad49f0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/entry/common.c (ffffffff81005181)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__prepare_exit_to_usermode
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff810322f7)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__set_personality_ia32
  - arch/x86/kernel/process_64.c:__set_personality_x32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff810343bf)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81036f8f)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81bcc4f1)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104177d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81043152)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81044bac)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81047297)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81068ad2)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/fork.c (ffffffff810a684e)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810ac09c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810b5496)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810be2a8)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81bc83a6)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810e848f)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff8113ccef)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/pid_namespace.c (ffffffff811856a8)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8118f5dc)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff811abc21)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff81248ecf)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81249255)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In mm/oom_kill.c (ffffffff8125752e)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff813a7d50)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In drivers/idle/intel_idle.c (ffffffff8167e8f4)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178a48d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff81bcc973)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process_64.c (ffffffff810336ff)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81c35f1d)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff8103804f)
Location: include/linux/thread_info.h:91
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81c451b4)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104189d)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81043129)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104463c)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81046ae7)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a772)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/fork.c (ffffffff810a13b2)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810a773c)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810b959c)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81c410fc)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810e607f)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff811373ff)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff8113babc)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff8113be65)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
```
```
In kernel/pid_namespace.c (ffffffff811827b8)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/events/uprobes.c (ffffffff812535df)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff812537d5)
Location: include/linux/thread_info.h:91
Inline: True
```
```
In mm/oom_kill.c (ffffffff8126210e)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff813b8bdd)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In drivers/idle/intel_idle.c (ffffffff8169d5f4)
Location: include/linux/thread_info.h:91
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a140d)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c454d3)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process_64.c (ffffffff8103529f)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81c2839e)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81039b8f)
Location: include/linux/thread_info.h:91
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81c38431)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104329d)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044a39)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104628c)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81048517)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b239)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/fork.c (ffffffff810a2121)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810a87cc)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810bad41)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81c3307b)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810e8049)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff811381af)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff8113cd8c)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff8113d142)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/pid_namespace.c (ffffffff81183918)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/events/uprobes.c (ffffffff81257bff)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81257df5)
Location: include/linux/thread_info.h:91
Inline: True
```
```
In mm/oom_kill.c (ffffffff81266b9e)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/io_uring.c (ffffffff8139ee86)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/io-wq.c (ffffffff813a336b)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/coredump.c (ffffffff813bfcda)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In drivers/idle/intel_idle.c (ffffffff8168037b)
Location: include/linux/thread_info.h:91
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81783f9d)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c38753)
Location: include/linux/thread_info.h:91
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process_64.c (ffffffff8103a57f)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81d4650e)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff8103f53f)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81d56cbe)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104960a)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104acd3)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104c96c)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8104ee57)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810549bf)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d56)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/mm/tlb.c (ffffffff8109b297)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff810b2f11)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810ba2ac)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810cd5ad)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81d51a73)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810ff709)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff8115af39)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff8115feac)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff8116026c)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
```
```
In kernel/pid_namespace.c (ffffffff811ab9f8)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/events/uprobes.c (ffffffff81293501)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81293965)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In mm/oom_kill.c (ffffffff812a339e)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/io_uring.c (ffffffff813ef165)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
```
```
In fs/io-wq.c (ffffffff813f2829)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/coredump.c (ffffffff8140fb0a)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In drivers/idle/intel_idle.c (ffffffff816f50e8)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180a9d6)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff81d57033)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process_64.c (ffffffff810415ff)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81f147dc)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81046bb5)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81f28f36)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810539ca)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054887)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpregs_restore_userregs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810555d7)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpregs_restore_userregs
```
```
In arch/x86/kernel/ptrace.c (ffffffff81057a3c)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8105a0a7)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106070f)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8108479f)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/mm/tlb.c (ffffffff810ae75b)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff810c91e2)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810d0d5b)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810e551b)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81f21f95)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_policy.c (ffffffff81133718)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff81184843)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff8118a34f)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff8118a772)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/pid_namespace.c (ffffffff811dd16c)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/events/uprobes.c (ffffffff812e8fd1)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff812e943f)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In mm/oom_kill.c (ffffffff812fb2ae)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff81484803)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In io_uring/io_uring.c (ffffffff816d8c60)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_sq_thread
```
```
In io_uring/io-wq.c (ffffffff816db39f)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In drivers/idle/intel_idle.c (ffffffff81821a11)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194a4b4)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff81f29a02)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process_64.c (ffffffff8104ad4f)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff820bbb5c)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81050cc5)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff820d4c26)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106143a)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062cea)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063920)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106522c)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81067ab7)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106ef5f)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81097a2f)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/mm/tlb.c (ffffffff810c8a0a)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff810e66d2)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810ef73b)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff81105bc3)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff820cc7e5)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_policy.c (ffffffff8115db38)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff811bfd8e)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff811c68bf)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff811c6d4e)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/pid_namespace.c (ffffffff81222b2c)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/events/uprobes.c (ffffffff81352b91)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff813531af)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In mm/oom_kill.c (ffffffff8136529e)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff81517d03)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In io_uring/io_uring.c (ffffffff8178a895)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff8179a285)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817a5965)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81952701)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aadb55)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff820d5862)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process_64.c (ffffffff8104b58f)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff8213d28c)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff810519f5)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff810607c6)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81062d0a)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810646e2)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065281)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff81066a7c)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81069367)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81070831)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
```
In arch/x86/mm/tlb.c (ffffffff810cc077)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff810f2042)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810fb6df)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff81111e53)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/vhost_task.c (ffffffff81139298)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/vhost_task.c:vhost_task_fn
```
```
In kernel/sched/core.c (ffffffff82150a95)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff811d286e)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff811d94df)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff811d9b5f)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/pid_namespace.c (ffffffff8123918c)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/events/uprobes.c (ffffffff81383da1)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff813843af)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In mm/oom_kill.c (ffffffff8139775e)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff8154f60b)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In io_uring/io_uring.c (ffffffff817cb285)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff817db2e5)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817e6925)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81af93fb)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
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
In arch/x86/kernel/process_64.c (ffffffff810527ff)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff8221f2ac)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81058c15)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81067871)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81069ffa)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106bba2)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c8ef)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106defc)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810707d7)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81078111)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
```
In arch/x86/mm/tlb.c (ffffffff810d4707)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff810fbc85)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff81104acd)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff8111b7f3)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/vhost_task.c (ffffffff81144058)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/vhost_task.c:vhost_task_fn
```
```
In kernel/sched/core.c (ffffffff822338c4)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff811e74ee)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff82223fa7)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
```
In kernel/entry/kvm.c (ffffffff811ef80f)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/pid_namespace.c (ffffffff81252e5c)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/events/uprobes.c (ffffffff813ad1f1)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff813ad7bf)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In mm/oom_kill.c (ffffffff813c158e)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff8158544b)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In io_uring/io_uring.c (ffffffff8180f825)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff8181f605)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In io_uring/io-wq.c (ffffffff8182c6e5)
Location: include/linux/thread_info.h:92
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4ca1b)
Location: include/linux/thread_info.h:92
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
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
In arch/arm64/kernel/debug-monitors.c (ffff800010085fb8)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:user_disable_single_step
```
```
In arch/arm64/kernel/fpsimd.c (ffff800010088188)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:fpsimd_update_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_restore_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_flush_thread
  - arch/arm64/kernel/fpsimd.c:fpsimd_thread_switch
  - arch/arm64/kernel/fpsimd.c:sve_set_vector_length
```
```
In arch/arm64/kernel/process.c (ffff80001008987c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:set_tagged_addr_ctrl
  - arch/arm64/kernel/process.c:arch_dup_task_struct
  - arch/arm64/kernel/process.c:flush_thread
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008d530)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:sve_set
```
```
In arch/arm64/kernel/signal.c (ffff800010093298)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
```
```
In arch/arm64/kernel/syscall.c (ffff80001009db2c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/arm64/kernel/syscall.c:el0_svc_handler
```
```
In arch/arm64/kernel/ssbd.c (ffff8000100abfe4)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
```
```
In arch/arm64/kvm/fpsimd.c (ffff8000100dadf0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp
```
```
In kernel/fork.c (ffff8000100f3e00)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffff8000100fac5c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffff800010109584)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffff800010110c18)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffff800010da155c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/pid_namespace.c (ffff8000101e7af0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffff8000101f1894)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffff80001020ed98)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffff8000102a7f8c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/oom_kill.c (ffff8000102b87e4)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/binfmt_elf.c (ffff80001041f124)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffff800010428ce8)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c101c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
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
In arch/arm/kernel/elf.c (c030ac7c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/arm/kernel/elf.c:elf_set_personality
```
```
In arch/arm/kernel/signal.c (c030e784)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:do_work_pending
```
```
In kernel/fork.c (c0351dc0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c0358b68)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (c0363204)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (c036837c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (c0e995a0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/pid_namespace.c (c0427ec0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (c0431d60)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (c044d8e0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (c04d75c0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/oom_kill.c (c04e4fc8)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (c05f1a24)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/char/tpm/tpm_tis_core.c (c09b965c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
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
In arch/powerpc/kernel/ptrace.c (c000000000018a14)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:ptrace_disable
```
```
In arch/powerpc/kernel/process.c (c000000000022388)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:copy_thread_tls
  - arch/powerpc/kernel/process.c:restore_tm_state
```
```
In arch/powerpc/kernel/signal.c (c000000000023700)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
  - arch/powerpc/kernel/signal.c:do_notify_resume
```
```
In kernel/fork.c (c0000000001393e4)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c000000000142020)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (c00000000014ecb4)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (c000000000159290)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (c000000000ee25d8)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (c00000000018ee80)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (c0000000001f3880)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/pid_namespace.c (c000000000258480)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (c000000000265b38)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (c00000000028d400)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (c00000000035be30)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/oom_kill.c (c000000000370a14)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (c00000000053902c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/char/tpm/tpm_tis_core.c (c000000000962ee4)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/cpuidle-pseries.c (c000000000c224b4)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
```
```
In drivers/cpuidle/cpuidle-powernv.c (c000000000c22b7c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
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
In arch/riscv/kernel/ptrace.c (ffffffe0000b62b4)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:ptrace_disable
```
```
In arch/riscv/kernel/signal.c (ffffffe0000b6a48)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:do_notify_resume
```
```
In kernel/fork.c (ffffffe0000bfdea)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffe0000c4a82)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffe0000cc9a2)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffe0000d0770)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffe0008c4dfa)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/pid_namespace.c (ffffffe00015cf12)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffe0001651ea)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffe00016fa18)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In mm/oom_kill.c (ffffffe0001dc53c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffe0002c6e44)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffe0005724e4)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
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
In arch/x86/entry/common.c (ffffffff81004825)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff8102fc1c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81031ce7)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81a7326c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e784)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040048)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff810421d0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81043b77)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a73420)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/fork.c (ffffffff81098334)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109e725)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a7de6)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810af95a)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81a6e79d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810da228)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff811269dc)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/pid_namespace.c (ffffffff8116bda8)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81174fe9)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8118ef11)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff8121518f)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81215525)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In mm/oom_kill.c (ffffffff81222d6e)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff8135ac69)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff815c8afd)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169b99d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a73860)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/entry/common.c (ffffffff81002e73)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff8101f63c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81021ab0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81a2f62c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102df84)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f848)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81031890)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810331a7)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f7d0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/fork.c (ffffffff81086d7a)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8108d13c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810967b6)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff8109e280)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81a2ab97)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810c921a)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff8111943c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/pid_namespace.c (ffffffff8115efa2)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81168189)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff81182091)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff81207eff)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81208285)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In mm/oom_kill.c (ffffffff81215f1e)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff8134b90d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b6d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167938d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2fbda)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/entry/common.c (ffffffff810047e5)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff8102fa7c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81031b47)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81adf67c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e5c4)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fe88)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042010)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810439b7)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf830)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/fork.c (ffffffff810982e4)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109e6d5)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a7346)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810aeeba)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81adabad)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810d6575)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff811248cc)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/pid_namespace.c (ffffffff81169b78)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81172db9)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8118cce1)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff81212f2f)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff812132c5)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In mm/oom_kill.c (ffffffff81220b0e)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff81358739)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff815c908d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816c9c0d)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff81adfc70)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/entry/common.c (ffffffff81004925)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/process_64.c (ffffffff810308cc)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81032a0e)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81aebe0c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103f754)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104122c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff810433f0)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81044db7)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81aec000)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/fork.c (ffffffff8109fedb)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a65ee)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810af2d6)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b7192)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81ae705f)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810e1e75)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/livepatch/transition.c (ffffffff81130f1c)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/pid_namespace.c (ffffffff81177298)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81180623)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8119a671)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff81221ea9)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81222265)
Location: include/linux/thread_info.h:58
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122fcae)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In fs/coredump.c (ffffffff8136b5c8)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/idle/intel_idle.c (ffffffff815e2eed)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e40e8)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/cpuidle/poll_state.c (ffffffff81aec470)
Location: include/linux/thread_info.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
</ul>
