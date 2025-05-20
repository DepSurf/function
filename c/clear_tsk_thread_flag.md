# Function: <code>clear_tsk_thread_flag</code>

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
In arch/x86/kernel/traps.c (ffffffff8102f273)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103943d)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103b893)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
  - arch/x86/kernel/ptrace.c:ptrace_disable
```
```
In arch/x86/kernel/step.c (ffffffff8103dc85)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051a2b)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
```
In kernel/fork.c (ffffffff8107e84f)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff81082741)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff8108b57a)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8108dbf2)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff8181faec)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/auditsc.c (ffffffff81128262)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8113fd19)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff81188b10)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81189779)
Location: include/linux/sched.h:2859
Inline: True
```
```
In fs/coredump.c (ffffffff8126f863)
Location: include/linux/sched.h:2859
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/traps.c (ffffffff8102e2ef)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81038446)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c8c2)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103dccd)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051bbb)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
```
In kernel/fork.c (ffffffff810804bd)
Location: include/linux/sched.h:3136
Inline: True
```
```
In kernel/exit.c (ffffffff8108577a)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff8108f091)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81090c72)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff8189a221)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/auditsc.c (ffffffff8113040c)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff81148379)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff8119b1e0)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8119be5b)
Location: include/linux/sched.h:3136
Inline: True
```
```
In fs/coredump.c (ffffffff8129b52c)
Location: include/linux/sched.h:3136
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/traps.c (ffffffff8102e247)
Location: include/linux/sched.h:3292
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81037ecd)
Location: include/linux/sched.h:3292
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c142)
Location: include/linux/sched.h:3292
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103d597)
Location: include/linux/sched.h:3292
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff81084e27)
Location: include/linux/sched.h:3292
Inline: True
```
```
In kernel/exit.c (ffffffff8108a6fc)
Location: include/linux/sched.h:3292
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81093116)
Location: include/linux/sched.h:3292
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81095c05)
Location: include/linux/sched.h:3292
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff818ce84a)
Location: include/linux/sched.h:3292
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/auditsc.c (ffffffff8113a17c)
Location: include/linux/sched.h:3292
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff81152239)
Location: include/linux/sched.h:3292
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff811aabeb)
Location: include/linux/sched.h:3292
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811ab83b)
Location: include/linux/sched.h:3292
Inline: True
```
```
In fs/coredump.c (ffffffff812b00eb)
Location: include/linux/sched.h:3292
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/traps.c (ffffffff8102c357)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81035fa7)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103a182)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103b5e7)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff81081cc7)
Location: include/linux/sched.h:1487
Inline: True
```
```
In kernel/exit.c (ffffffff81087767)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81090226)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81092bb5)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81905c71)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff810f931f)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/auditsc.c (ffffffff8113b7bc)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff81154819)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff811b210c)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811b2ca7)
Location: include/linux/sched.h:1487
Inline: True
```
```
In fs/coredump.c (ffffffff812bd5ba)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/traps.c (ffffffff8102d257)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81038307)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103cb92)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103e007)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff81088591)
Location: include/linux/sched.h:1521
Inline: True
```
```
In kernel/exit.c (ffffffff8108e4f7)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81097096)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81099a95)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff8198fced)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff81103d54)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_switch_task
```
```
In kernel/auditsc.c (ffffffff8114851b)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff81161039)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff811c5d1c)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811c68f7)
Location: include/linux/sched.h:1521
Inline: True
```
```
In fs/coredump.c (ffffffff812e0e89)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/traps.c (ffffffff8102e207)
Location: include/linux/sched.h:1637
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81039776)
Location: include/linux/sched.h:1637
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103e122)
Location: include/linux/sched.h:1637
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103f5b7)
Location: include/linux/sched.h:1637
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff8108c2f3)
Location: include/linux/sched.h:1637
Inline: True
```
```
In kernel/exit.c (ffffffff81091f51)
Location: include/linux/sched.h:1637
Inline: True
```
```
In kernel/ptrace.c (ffffffff8109a58c)
Location: include/linux/sched.h:1637
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff8109da65)
Location: include/linux/sched.h:1637
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff819ec539)
Location: include/linux/sched.h:1637
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff8110c1b4)
Location: include/linux/sched.h:1637
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_switch_task
```
```
In kernel/auditsc.c (ffffffff81156eeb)
Location: include/linux/sched.h:1637
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8116ff88)
Location: include/linux/sched.h:1637
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff811e61f8)
Location: include/linux/sched.h:1637
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811e6e37)
Location: include/linux/sched.h:1637
Inline: True
```
```
In fs/coredump.c (ffffffff8130d0bf)
Location: include/linux/sched.h:1637
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/traps.c (ffffffff8102f4c7)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103aacd)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103f702)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81040bb7)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff81093d0d)
Location: include/linux/sched.h:1650
Inline: True
```
```
In kernel/exit.c (ffffffff8109a241)
Location: include/linux/sched.h:1650
Inline: True
```
```
In kernel/ptrace.c (ffffffff810a27cc)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810a5d75)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81a277bb)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff811179a4)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_switch_task
```
```
In kernel/auditsc.c (ffffffff81163f3b)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8117db38)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff811f6d48)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811f7a67)
Location: include/linux/sched.h:1650
Inline: True
```
```
In fs/coredump.c (ffffffff81322988)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/traps.c (ffffffff810312c7)
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103d095)
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff810418d0)
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81043297)
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff8109843a)
Location: include/linux/sched.h:1723
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
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a7452)
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810aaa3e)
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81a98057)
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff81121ddc)
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/auditsc.c (ffffffff81170b49)
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8118a9e1)
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff8120eb15)
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8120f8a5)
Location: include/linux/sched.h:1723
Inline: True
```
```
In fs/coredump.c (ffffffff8134a3e9)
Location: include/linux/sched.h:1723
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/traps.c (ffffffff81031b87)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103d855)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042050)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810439f7)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff8109ea14)
Location: include/linux/sched.h:1716
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
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810ada76)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b103e)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81acf92d)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff8112e3fc)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/auditsc.c (ffffffff8117c9c9)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff811968f1)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff8121c155)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8121ced5)
Location: include/linux/sched.h:1716
Inline: True
```
```
In fs/coredump.c (ffffffff81362689)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/ioport.c (ffffffff81036f8f)
Location: include/linux/sched.h:1766
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81040ab9)
Location: include/linux/sched.h:1766
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff81044bac)
Location: include/linux/sched.h:1766
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81047297)
Location: include/linux/sched.h:1766
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In kernel/fork.c (ffffffff810a684e)
Location: include/linux/sched.h:1766
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
Location: include/linux/sched.h:1766
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810b5496)
Location: include/linux/sched.h:1766
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b8212)
Location: include/linux/sched.h:1766
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81bc83a6)
Location: include/linux/sched.h:1766
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff8113ccef)
Location: include/linux/sched.h:1766
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/auditsc.c (ffffffff8118f5dc)
Location: include/linux/sched.h:1766
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff811abc21)
Location: include/linux/sched.h:1766
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff812487e5)
Location: include/linux/sched.h:1766
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81249255)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/coredump.c (ffffffff813a7d50)
Location: include/linux/sched.h:1766
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
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
In arch/x86/kernel/ioport.c (ffffffff8103804f)
Location: include/linux/sched.h:1827
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81040a12)
Location: include/linux/sched.h:1827
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104463c)
Location: include/linux/sched.h:1827
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81046ae7)
Location: include/linux/sched.h:1827
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In kernel/fork.c (ffffffff810a13b2)
Location: include/linux/sched.h:1827
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810a773c)
Location: include/linux/sched.h:1827
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810b34c2)
Location: include/linux/sched.h:1827
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81c410fc)
Location: include/linux/sched.h:1827
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff811373ff)
Location: include/linux/sched.h:1827
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/events/uprobes.c (ffffffff81252ef5)
Location: include/linux/sched.h:1827
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff812537d5)
Location: include/linux/sched.h:1827
Inline: True
```
```
In fs/coredump.c (ffffffff813b8bdd)
Location: include/linux/sched.h:1827
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
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
In arch/x86/kernel/ioport.c (ffffffff81039b8f)
Location: include/linux/sched.h:1849
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8104240a)
Location: include/linux/sched.h:1849
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104628c)
Location: include/linux/sched.h:1849
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81048517)
Location: include/linux/sched.h:1849
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff810a2121)
Location: include/linux/sched.h:1849
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810a87cc)
Location: include/linux/sched.h:1849
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810b4af2)
Location: include/linux/sched.h:1849
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81c3307b)
Location: include/linux/sched.h:1849
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff811381af)
Location: include/linux/sched.h:1849
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/events/uprobes.c (ffffffff81257235)
Location: include/linux/sched.h:1849
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81257df5)
Location: include/linux/sched.h:1849
Inline: True
```
```
In fs/coredump.c (ffffffff813bfcda)
Location: include/linux/sched.h:1849
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
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
In arch/x86/kernel/ioport.c (ffffffff8103f53f)
Location: include/linux/sched.h:1966
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81048757)
Location: include/linux/sched.h:1966
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104c96c)
Location: include/linux/sched.h:1966
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8104ee57)
Location: include/linux/sched.h:1966
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff810b2f11)
Location: include/linux/sched.h:1966
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810ba2ac)
Location: include/linux/sched.h:1966
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810c99ee)
Location: include/linux/sched.h:1966
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81d51a73)
Location: include/linux/sched.h:1966
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff8115af39)
Location: include/linux/sched.h:1966
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/events/uprobes.c (ffffffff81292fc5)
Location: include/linux/sched.h:1966
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81293965)
Location: include/linux/sched.h:1966
Inline: True
```
```
In fs/coredump.c (ffffffff8140fb0a)
Location: include/linux/sched.h:1966
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
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
In arch/x86/kernel/ioport.c (ffffffff81046bb5)
Location: include/linux/sched.h:1988
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81051a4a)
Location: include/linux/sched.h:1988
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff81057a3c)
Location: include/linux/sched.h:1988
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8105a0a7)
Location: include/linux/sched.h:1988
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff810c91e2)
Location: include/linux/sched.h:1988
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810d0d5b)
Location: include/linux/sched.h:1988
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810e143e)
Location: include/linux/sched.h:1988
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81f21f95)
Location: include/linux/sched.h:1988
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff81184843)
Location: include/linux/sched.h:1988
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/events/uprobes.c (ffffffff812e8a3b)
Location: include/linux/sched.h:1988
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff812e943f)
Location: include/linux/sched.h:1988
Inline: True
```
```
In fs/coredump.c (ffffffff81484803)
Location: include/linux/sched.h:1988
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
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
In arch/x86/kernel/ioport.c (ffffffff81050cc5)
Location: include/linux/sched.h:2015
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8105f0c6)
Location: include/linux/sched.h:2015
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106522c)
Location: include/linux/sched.h:2015
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81067ab7)
Location: include/linux/sched.h:2015
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In kernel/fork.c (ffffffff810e66d2)
Location: include/linux/sched.h:2015
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810ef73b)
Location: include/linux/sched.h:2015
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff811016be)
Location: include/linux/sched.h:2015
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff820cc7e5)
Location: include/linux/sched.h:2015
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff811bfd8e)
Location: include/linux/sched.h:2015
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/events/uprobes.c (ffffffff8135279b)
Location: include/linux/sched.h:2015
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff813531af)
Location: include/linux/sched.h:2015
Inline: True
```
```
In fs/coredump.c (ffffffff81517d03)
Location: include/linux/sched.h:2015
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
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
In arch/x86/kernel/ioport.c (ffffffff810519f5)
Location: include/linux/sched.h:2023
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff810607c6)
Location: include/linux/sched.h:2023
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff81066a7c)
Location: include/linux/sched.h:2023
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81069367)
Location: include/linux/sched.h:2023
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In kernel/fork.c (ffffffff810f2042)
Location: include/linux/sched.h:2023
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff810fb6df)
Location: include/linux/sched.h:2023
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff8110d81e)
Location: include/linux/sched.h:2023
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff82150a95)
Location: include/linux/sched.h:2023
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff811d286e)
Location: include/linux/sched.h:2023
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/events/uprobes.c (ffffffff813839ab)
Location: include/linux/sched.h:2023
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff813843af)
Location: include/linux/sched.h:2023
Inline: True
```
```
In fs/coredump.c (ffffffff8154f60b)
Location: include/linux/sched.h:2023
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
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
In arch/x86/kernel/ioport.c (ffffffff81058c15)
Location: include/linux/sched.h:1925
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81067871)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106defc)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810707d7)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In kernel/fork.c (ffffffff810fbc85)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffffffff81104acd)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff8111715e)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff822338c4)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff811e74ee)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/events/uprobes.c (ffffffff813ace0b)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff813ad7bf)
Location: include/linux/sched.h:1925
Inline: True
```
```
In fs/coredump.c (ffffffff8158544b)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
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
In arch/arm64/kernel/process.c (ffff800010089220)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:arch_dup_task_struct
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008d530)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:sve_set
```
```
In arch/arm64/kernel/ssbd.c (ffff8000100abfe4)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
```
```
In kernel/fork.c (ffff8000100f3e00)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
```
```
In kernel/exit.c (ffff8000100fac5c)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffff800010109584)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffff80001010cb64)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffff800010da155c)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/auditsc.c (ffff8000101f1894)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffff80001020ed98)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffff8000102a7ad0)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In fs/coredump.c (ffff800010428ce8)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/fork.c (c0351dc0)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c0358b68)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (c0363204)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (c0364ea4)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (c0e995a0)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/auditsc.c (c0431d60)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (c044d8e0)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (c04d6bd0)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In fs/coredump.c (c05f1a24)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:ptrace_disable
```
```
In arch/powerpc/kernel/process.c (c000000000022388)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:copy_thread_tls
```
```
In kernel/fork.c (c0000000001393e4)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c000000000142020)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (c00000000014ecb4)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (c000000000153b3c)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (c000000000ee25d8)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (c0000000001f3880)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/auditsc.c (c000000000265b38)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (c00000000028d400)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (c00000000035b148)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In fs/coredump.c (c00000000053902c)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:ptrace_disable
```
```
In kernel/fork.c (ffffffe0000bfdea)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffe0000c4a82)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffe0000cc9a2)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffe0000ce1d6)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffe0008c4dfa)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/auditsc.c (ffffffe0001651ea)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffe00016fa18)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In fs/coredump.c (ffffffe0002c6e44)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/traps.c (ffffffff81031ce7)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103d9d5)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff810421d0)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81043b77)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff81098334)
Location: include/linux/sched.h:1716
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
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a7de6)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810ab3ae)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81a6e79d)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff811269dc)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/auditsc.c (ffffffff81174fe9)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8118ef11)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff812147a5)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81215525)
Location: include/linux/sched.h:1716
Inline: True
```
```
In fs/coredump.c (ffffffff8135ac69)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/traps.c (ffffffff81021ab0)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8102d0c8)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff81031890)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810331a7)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff81086d7a)
Location: include/linux/sched.h:1716
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
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810967b6)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81099d4e)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81a2ab97)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff8111943c)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/auditsc.c (ffffffff81168189)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff81182091)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff81207515)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81208285)
Location: include/linux/sched.h:1716
Inline: True
```
```
In fs/coredump.c (ffffffff8134b90d)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/traps.c (ffffffff81031b47)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103d815)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042010)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810439b7)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff810982e4)
Location: include/linux/sched.h:1716
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
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a7346)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810aa90e)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81adabad)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff811248cc)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/auditsc.c (ffffffff81172db9)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8118cce1)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff81212545)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff812132c5)
Location: include/linux/sched.h:1716
Inline: True
```
```
In fs/coredump.c (ffffffff81358739)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In arch/x86/kernel/traps.c (ffffffff81032a0e)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103e963)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/ptrace.c (ffffffff810433f0)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81044db7)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff8109fedb)
Location: include/linux/sched.h:1716
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
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810af2d6)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b29ee)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/signal.c:flush_signals
```
```
In kernel/sched/core.c (ffffffff81ae705f)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/livepatch/transition.c (ffffffff81130f1c)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/auditsc.c (ffffffff81180623)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/tracepoint.c (ffffffff8119a671)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/events/uprobes.c (ffffffff812214c5)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81222265)
Location: include/linux/sched.h:1716
Inline: True
```
```
In fs/coredump.c (ffffffff8136b5c8)
Location: include/linux/sched.h:1716
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
</ul>

## Differences
