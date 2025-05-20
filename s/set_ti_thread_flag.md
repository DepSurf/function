# Function: <code>set_ti_thread_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_ti_thread_flag(struct thread_info *ti, int flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d012)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8102e397)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff8102f3a8)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff8103197d)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81038fb5)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103dc48)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810500d8)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064e09)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107810d)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff8118b905)
Location: include/linux/thread_info.h:69
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff8108b570)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff8108d139)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - kernel/signal.c:recalc_sigpending_tsk
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:ptrace_stop
```
```
In kernel/sched/core.c (ffffffff810aa379)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c3dfb)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/cgroup.c (ffffffff8111793c)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/auditsc.c (ffffffff811282e4)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8113b8b3)
Location: include/linux/thread_info.h:69
Inline: True
```
```
In kernel/tracepoint.c (ffffffff8113fc72)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff81188b57)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
```
```
In kernel/user-return-notifier.c (ffffffff811897a2)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In block/blk-cgroup.c (ffffffff813d90a4)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff81479435)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle_freeze
```
```
In drivers/tty/tty_io.c (ffffffff814e0235)
Location: include/linux/thread_info.h:69
Inline: True
```
```
In drivers/base/core.c (ffffffff81547db0)
Location: include/linux/thread_info.h:69
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff816bc079)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
```
In net/core/net-sysfs.c (ffffffff81736b8f)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
```
In net/ipv4/devinet.c (ffffffff81792e27)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff817cd3b3)
Location: include/linux/thread_info.h:69
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
```
**Symbols:**

```
ffffffff8118b905-ffffffff8118b914: set_ti_thread_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_ti_thread_flag(struct thread_info *ti, int flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c012)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8102d145)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff8102e3cc)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81030a8d)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81037ff7)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103db17)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810502c0)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064bb9)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810795eb)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff8119e629)
Location: include/linux/thread_info.h:70
Inline: False
```
```
In kernel/ptrace.c (ffffffff8108e570)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81091b17)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff810acfd3)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c7b01)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/cgroup.c (ffffffff8111f9a3)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/auditsc.c (ffffffff8113048b)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff811443db)
Location: include/linux/thread_info.h:70
Inline: True
```
```
In kernel/tracepoint.c (ffffffff811482d2)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff8119bdde)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8119be82)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In block/blk-cgroup.c (ffffffff8141ee1f)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff814c796c)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_io.c (ffffffff81531ab0)
Location: include/linux/thread_info.h:70
Inline: True
```
```
In drivers/base/core.c (ffffffff81599a10)
Location: include/linux/thread_info.h:70
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff8171d989)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
```
In net/core/net-sysfs.c (ffffffff817a2d5c)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
```
In net/ipv4/devinet.c (ffffffff818005dd)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8183aaa6)
Location: include/linux/thread_info.h:70
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff8119e629-ffffffff8119e638: set_ti_thread_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_ti_thread_flag(struct thread_info *ti, int flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c012)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8102cfe0)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff8102e324)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff810306ed)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff818d3b67)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103d3f3)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff818d3d49)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/paravirt.c (ffffffff81068089)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d3d4)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff811ae056)
Location: include/linux/thread_info.h:41
Inline: False
```
```
In kernel/ptrace.c (ffffffff810931c0)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81096aa7)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff810b305f)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810cd809)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/cgroup.c (ffffffff81127f4d)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/auditsc.c (ffffffff8113a1f7)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8114e28f)
Location: include/linux/thread_info.h:41
Inline: True
```
```
In kernel/tracepoint.c (ffffffff81152194)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff811ab7c5)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811ab862)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In block/blk-cgroup.c (ffffffff8143a3df)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff814e9886)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_io.c (ffffffff8155e1e7)
Location: include/linux/thread_info.h:41
Inline: True
```
```
In drivers/base/core.c (ffffffff815c7ce0)
Location: include/linux/thread_info.h:41
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff818d4049)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
```
In net/core/net-sysfs.c (ffffffff817d17bc)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
```
In net/ipv4/devinet.c (ffffffff8183153d)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8186c4a6)
Location: include/linux/thread_info.h:41
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff811ae056-ffffffff811ae064: set_ti_thread_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_ti_thread_flag(struct thread_info *ti, int flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102a1a2)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8102b23f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff8102c427)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff8102e94d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8190aca7)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103b443)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8190aea9)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/paravirt.c (ffffffff810673a0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107bbd4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81084230)
Location: include/linux/thread_info.h:53
Inline: False
```
```
In kernel/ptrace.c (ffffffff81090238)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81093db7)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff810aef3c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810ca229)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff810f90af)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112ac2b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/auditsc.c (ffffffff8113b837)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8115093b)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/tracepoint.c (ffffffff81154774)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff811b2c37)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811b2cc2)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In block/blk-cgroup.c (ffffffff81447b51)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff814f54a6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8157cfb3)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (ffffffff815dc970)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff8190b1d9)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
```
In net/core/net-sysfs.c (ffffffff817f0ba8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
```
In net/ipv4/devinet.c (ffffffff81852ae6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8188e48e)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff81084230-ffffffff8108423e: set_ti_thread_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_ti_thread_flag(struct thread_info *ti, int flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102af72)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8102bf72)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff8102d327)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81030809)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81995017)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103de5f)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8199521c)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b5f9)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810822d7)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81086da3)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/fork.c (ffffffff8108ab2d)
Location: include/linux/thread_info.h:57
Inline: False
```
```
In kernel/exit.c (ffffffff8108f8a0)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810970a8)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff8109ac97)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff810b6192)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d1a09)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/power/user.c (ffffffff810e8a1c)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/livepatch/transition.c (ffffffff81103aaf)
Location: include/linux/thread_info.h:57
Inline: True
```
```
In kernel/module.c (ffffffff81125258)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811379c1)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/auditsc.c (ffffffff81148596)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8115cb75)
Location: include/linux/thread_info.h:57
Inline: True
```
```
In kernel/tracepoint.c (ffffffff81160f94)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/trace_kprobe.c (ffffffff81190c3f)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/callchain.c (ffffffff811c33be)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffffffff811c6887)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811c6912)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/maccess.c (ffffffff811d2dc9)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812740a7)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff8127b887)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff812aa21b)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff812b4537)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/binfmt_elf.c (ffffffff812da5fa)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812dd712)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In security/integrity/iint.c (ffffffff8141de0b)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-cgroup.c (ffffffff81474751)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff81535d29)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_jobctrl.c (ffffffff815e18e3)
Location: include/linux/thread_info.h:57
Inline: True
```
```
In drivers/base/core.c (ffffffff816439b0)
Location: include/linux/thread_info.h:57
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81995569)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/socket.c (ffffffff81825297)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - net/socket.c:kernel_sock_ioctl
  - net/socket.c:kernel_sock_ioctl
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/net-sysfs.c (ffffffff8186c1af)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/compat.c (ffffffff81877765)
Location: include/linux/thread_info.h:57
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff818d28f6)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv4/ipmr.c (ffffffff818e93ee)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff8190f9ee)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
```
In net/ipv6/exthdrs.c (ffffffff8193ebb7)
Location: include/linux/thread_info.h:57
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options_kern
  - net/ipv6/exthdrs.c:ipv6_renew_options_kern
```
**Symbols:**

```
ffffffff8108ab2d-ffffffff8108ab3b: set_ti_thread_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c17f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8102d242)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff8102e349)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81031a7a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff819f158f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103f3ff)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff819f177a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106e2c9)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81085997)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff8108d56e)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/exit.c (ffffffff81093410)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff8109a59a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff8109ebd4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff819ec5ec)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c40c6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/power/user.c (ffffffff810f0d2c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/livepatch/transition.c (ffffffff8110c2fc)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/module.c (ffffffff8113360d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8114626d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/auditsc.c (ffffffff81156f66)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8116bf29)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/tracepoint.c (ffffffff8116fee4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a615c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/core.c (ffffffff811dfe45)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff811e3760)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffffffff811e6d05)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811e6e4f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff811ea05e)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In mm/maccess.c (ffffffff811f414d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff8129ae17)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812a20e7)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff812d1f8f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff812dbb57)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/binfmt_elf.c (ffffffff81306216)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81309bae)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In security/integrity/iint.c (ffffffff814500bb)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-cgroup.c (ffffffff814a8864)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff8156b8ca)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8161ab40)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (ffffffff8167ed60)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff819f1abe)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/socket.c (ffffffff81870255)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/net-sysfs.c (ffffffff818bca91)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/compat.c (ffffffff818c91e2)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
```
In net/ipv4/devinet.c (ffffffff81928e9f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv4/ipmr.c (ffffffff8193f01d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff81967243)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
**Symbols:**

```
ffffffff8110c2fc-ffffffff8110c307: set_ti_thread_flag.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d22f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8102e492)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff8102f609)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81032d8a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81a2c9bf)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff810409ff)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81044e65)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2cc1a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/paravirt.c (ffffffff81074299)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108c707)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810956c8)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/exit.c (ffffffff8109b6d0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a27da)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810a6eb4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81a2786e)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810cd3c6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/power/user.c (ffffffff810fc3bc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/rcu/tree.c (ffffffff81114a65)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/livepatch/transition.c (ffffffff81117aec)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/module.c (ffffffff8113ef82)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151e13)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/auditsc.c (ffffffff81163fb6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8117993f)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/tracepoint.c (ffffffff8117da94)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/core.c (ffffffff811f0295)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff811f3c2e)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffffffff811f7865)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811f7a7f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff811fabce)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In mm/maccess.c (ffffffff812064dd)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812afd17)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812b6e07)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff812e736c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff812f1247)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/binfmt_elf.c (ffffffff8131b9a6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8131f3ae)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In security/integrity/iint.c (ffffffff8146d09b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-cgroup.c (ffffffff814c2e1f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff8158344a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81637db0)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (ffffffff8169f1a0)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2cfdd)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/socket.c (ffffffff81890e25)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/net-sysfs.c (ffffffff818e3d41)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/compat.c (ffffffff818f4092)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
```
In net/ipv4/devinet.c (ffffffff8195818f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv4/ipmr.c (ffffffff8196f76d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff8199c713)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
**Symbols:**

```
ffffffff81117aec-ffffffff81117af7: set_ti_thread_flag.constprop.8 (STB_LOCAL)
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
In arch/x86/kernel/process_64.c (ffffffff8102f14f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff810301f1)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff81031402)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81034b9a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81a9cb1f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e420)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f15e)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff810430be)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810477f5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd88)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077de9)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810906fc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81099878)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109fd3f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a7460)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810acf64)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81a98115)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d5786)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/power/user.c (ffffffff81104c0a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/rcu/tree.c (ffffffff8111a53c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81121faf)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/stacktrace.c (ffffffff8112613d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff8114a3a6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115dacf)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff8115e398)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/auditsc.c (ffffffff81170bc1)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff811863cd)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/tracepoint.c (ffffffff8118a92d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/bpf/cgroup.c (ffffffff811f86a8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffff81207ae6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff8120b916)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffffffff8120f618)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8120f8bf)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff812122d5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In mm/maccess.c (ffffffff8121da7d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812ca387)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812d3b6a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff813059c0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff813138aa)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffff81330afb)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffff8134336f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81346cff)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffff81365237)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/request_key.c (ffffffff81431a1b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In security/integrity/iint.c (ffffffff8149a78b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-cgroup.c (ffffffff814f159f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b95)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8166c077)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (ffffffff816d77e0)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a9d14f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/socket.c (ffffffff818db715)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/net-sysfs.c (ffffffff81932721)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff819bcbe0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv4/ipmr.c (ffffffff819d8fd8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff81a0898c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
In arch/x86/kernel/process_64.c (ffffffff8102faaf)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff81030b31)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff81031cc2)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff810353d3)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81ad436f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103ebe0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f7c7)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff8104381e)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048035)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad45d8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078e59)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109125c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810a0206)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a6342)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810ada88)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810b3584)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81acf9eb)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810dfd96)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/power/user.c (ffffffff81110fba)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/rcu/tree.c (ffffffff8112693c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff8112e5cf)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/stacktrace.c (ffffffff8113210d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff81156005)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811696df)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff81169f88)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/auditsc.c (ffffffff8117ca41)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff811923e9)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffffffff8119683d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/bpf/cgroup.c (ffffffff81205518)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffff81214e56)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff81218bf6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffffffff8121ccc8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8121ceef)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff8121fab5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In mm/maccess.c (ffffffff8122b51d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812dbda7)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812e56fa)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff81318a50)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff813267ba)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffff813444a9)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffff8135b7ad)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135f00d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffff8137d4c7)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/request_key.c (ffffffff8144b77b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In security/integrity/iint.c (ffffffff814b498b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-cgroup.c (ffffffff8150abda)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff815d4dd5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8168e6e7)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (ffffffff816fb900)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81ad499f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/socket.c (ffffffff8190de65)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/net-sysfs.c (ffffffff81965261)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff819f38d0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv4/ipmr.c (ffffffff81a0fd48)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff81a3f8cc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
In arch/x86/kernel/process_64.c (ffffffff8103235f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__set_personality_ia32
  - arch/x86/kernel/process_64.c:__set_personality_x32
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff810344b0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81037244)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff81bcc45f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81041c35)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042d72)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff810471ae)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c106)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104dbeb)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81068af9)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108014c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In kernel/fork.c (ffffffff810a6cc8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_seccomp
```
```
In kernel/exit.c (ffffffff810ae0f9)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810b54a8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810bc500)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/kthread.c (ffffffff810d1092)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff810dde4b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e8096)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In kernel/rcu/tree.c (ffffffff81136cba)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_sched_exp_online_cleanup
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff8113ce4c)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/stacktrace.c (ffffffff8114155e)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117b362)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff8117bafc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/auditsc.c (ffffffff8118f660)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff811a72ad)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_strict
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/tracepoint.c (ffffffff811abb6d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/core.c (ffffffff812320e7)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/callchain.c (ffffffff812448b2)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffffffff81249058)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8124926f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff8124bda3)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In mm/maccess.c (ffffffff8125841b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In fs/read_write.c (ffffffff81311c16)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
```
```
In fs/exec.c (ffffffff8131e5a0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/splice.c (ffffffff81351d1c)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In security/keys/request_key.c (ffffffff8149d786)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff8156bbab)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff8167e91b)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81740997)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (ffffffff817b6248)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In drivers/cpuidle/poll_state.c (ffffffff81bcc95d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/socket.c (ffffffff819df46d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/net-sysfs.c (ffffffff81a3868e)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/devinet.c (ffffffff81ae12e2)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81b34a3a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In arch/x86/kernel/process_64.c (ffffffff81032d3f)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ioport.c (ffffffff81038304)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff81c4515f)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81041c86)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042a94)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff810469fe)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b63e)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d11b)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a799)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fd6c)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In kernel/signal.c (ffffffff810b77f0)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/sched/core.c (ffffffff810da3bb)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e5cb6)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In kernel/sched/membarrier.c (ffffffff81108feb)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff8113231a)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_sched_exp_online_cleanup
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81be33f7)
Location: include/linux/thread_info.h:86
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178237)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff8117894c)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/events/uprobes.c (ffffffff81253768)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff812537ef)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff81256239)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff814bb2a6)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff815868f2)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff8169d61b)
Location: include/linux/thread_info.h:86
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8175c8cc)
Location: include/linux/thread_info.h:86
Inline: True
```
```
In drivers/base/core.c (ffffffff817cb6b8)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c454bd)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/net-sysfs.c (ffffffff81a3b8cc)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/devinet.c (ffffffff81aee182)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81b4351a)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In arch/x86/kernel/process_64.c (ffffffff8103484f)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ioport.c (ffffffff81039e44)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff81c383df)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81043686)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044482)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff810482fc)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d2ee)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ec9b)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b260)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080e2c)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In kernel/signal.c (ffffffff810b8d60)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/sched/core.c (ffffffff810dc9e3)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e7c76)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In kernel/sched/membarrier.c (ffffffff8110b09b)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff81bd48d4)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81bd5343)
Location: include/linux/thread_info.h:86
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178daa)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff811794bf)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/events/uprobes.c (ffffffff81257d88)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81257e0f)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff8125a80b)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff814c1166)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff8158d602)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff816803a2)
Location: include/linux/thread_info.h:86
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8174075c)
Location: include/linux/thread_info.h:86
Inline: True
```
```
In drivers/base/core.c (ffffffff817af028)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c3873d)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/net-sysfs.c (ffffffff81a22d3e)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:duplex_show
```
```
In net/ipv4/devinet.c (ffffffff81ad98e0)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81b31baa)
Location: include/linux/thread_info.h:86
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In arch/x86/kernel/process_64.c (ffffffff81039b4f)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ioport.c (ffffffff8103f7f4)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff81d56c6f)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81049b07)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a969)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff8104ec0e)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054a1e)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81056d0b)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d7d)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108fd9c)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In kernel/signal.c (ffffffff810cb2f0)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/sched/core.c (ffffffff810f150b)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810ff356)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In kernel/sched/membarrier.c (ffffffff811298fb)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff81caed4c)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81cb0052)
Location: include/linux/thread_info.h:87
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811a06da)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff811a0dcf)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/events/uprobes.c (ffffffff812938f8)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8129397f)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff812965fb)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff81519bd6)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff815f30a6)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff816f510f)
Location: include/linux/thread_info.h:87
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817c11ba)
Location: include/linux/thread_info.h:87
Inline: True
```
```
In drivers/base/core.c (ffffffff81838244)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In drivers/cpuidle/poll_state.c (ffffffff81d5701d)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/net-sysfs.c (ffffffff81ad72d5)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
```
```
In net/ipv4/devinet.c (ffffffff81b98a1a)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81bf907a)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81040a5f)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ioport.c (ffffffff81046d16)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:io_bitmap_exit
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff81f28edf)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810538da)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054e63)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff81059d9c)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81060724)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810847d4)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0c43)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In kernel/signal.c (ffffffff810e493f)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/sched/core.c (ffffffff8110d8fb)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/build_policy.c (ffffffff8112ecd6)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:idle_inject_timer_fn
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8113eeab)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff8117dbe0)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_flavor_sched_clock_irq
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
Direct callers:
  - kernel/rcu/tree.c:print_cpu_stall
```
```
In kernel/livepatch/transition.c (ffffffff81e60bf7)
Location: include/linux/thread_info.h:87
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0e37)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff811d15ce)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/events/uprobes.c (ffffffff812e93b5)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff812e945f)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff812ec5b1)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff815ac856)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff816a454b)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff81821a44)
Location: include/linux/thread_info.h:87
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff818fdb9b)
Location: include/linux/thread_info.h:87
Inline: True
```
```
In drivers/base/core.c (ffffffff8197a5b8)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In drivers/cpuidle/poll_state.c (ffffffff81f299ec)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/net-sysfs.c (ffffffff81c579f1)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/devinet.c (ffffffff81d2a899)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81d92459)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
```
**Symbols:**

```
ffffffff81179870-ffffffff8117987b: set_ti_thread_flag.constprop.0 (STB_LOCAL)
ffffffff81e60bf7-ffffffff81e60c03: set_ti_thread_flag.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/process_64.c (ffffffff81049d6f)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ioport.c (ffffffff81050e46)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:io_bitmap_exit
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff820d4bcf)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106127e)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810629b9)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff8106795c)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106ef74)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81097a64)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b89b3)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In kernel/signal.c (ffffffff81104fbf)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/kthread.c (ffffffff8111d7b6)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff8113461b)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/build_policy.c (ffffffff81158aa6)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:idle_inject_timer_fn
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff811692fb)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff811b6a84)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff811bfd6a)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_start_transition
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81214997)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff8121518e)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/events/uprobes.c (ffffffff81353115)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff813531df)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff813568e1)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff81656d46)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff81763239)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff81952734)
Location: include/linux/thread_info.h:87
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81a5730c)
Location: include/linux/thread_info.h:87
Inline: True
```
```
In drivers/base/core.c (ffffffff81ae7418)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In drivers/cpuidle/poll_state.c (ffffffff820d584c)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/net-sysfs.c (ffffffff81e0d7b1)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/devinet.c (ffffffff81ef23a9)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81f60b79)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In arch/x86/kernel/process_64.c (ffffffff8104a38f)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ioport.c (ffffffff81051b76)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:io_bitmap_exit
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff810607cc)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106207b)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810643bd)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff8106920c)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81070846)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bbb83)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In kernel/signal.c (ffffffff8111123f)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/kthread.c (ffffffff8112a9a6)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff811524a6)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/build_policy.c (ffffffff81168c76)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:idle_inject_timer_fn
```
```
In kernel/sched/build_utility.c (ffffffff811799fb)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff811c74b4)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff811d284a)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_start_transition
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a2b7)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff8122aabe)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/events/uprobes.c (ffffffff81384315)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff813843df)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff8138807c)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff8168f67f)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff817a1d63)
Location: include/linux/thread_info.h:87
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81aa18f4)
Location: include/linux/thread_info.h:87
Inline: True
```
```
In drivers/base/core.c (ffffffff81b35848)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81e80a01)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/devinet.c (ffffffff81f51e79)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81fc09a9)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In arch/x86/xen/enlighten_pv.c (ffffffff8103d03f)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_context_switch
```
```
In arch/x86/kernel/process_64.c (ffffffff810515ef)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ioport.c (ffffffff81058d96)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:io_bitmap_exit
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff81067877)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106904b)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b897)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff8107067c)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81078126)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In kernel/signal.c (ffffffff8111abbe)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/kthread.c (ffffffff81135036)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff8115e36b)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/build_policy.c (ffffffff81175f26)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:idle_inject_timer_fn
```
```
In kernel/sched/build_utility.c (ffffffff8118742b)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff811d79d4)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff811e74ca)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_start_transition
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81242157)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff81242a7e)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/events/uprobes.c (ffffffff813ad725)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff813ad7ef)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff813b1adc)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff816cbc0f)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff817e58b0)
Location: include/linux/thread_info.h:87
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81af4354)
Location: include/linux/thread_info.h:87
Inline: True
```
```
In drivers/base/core.c (ffffffff81b8d268)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81f419be)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/devinet.c (ffffffff82018152)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8208de6a)
Location: include/linux/thread_info.h:87
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In arch/arm64/kernel/fpsimd.c (ffff8000100874a4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:fpsimd_flush_cpu_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_thread_switch
  - arch/arm64/kernel/fpsimd.c:sve_set_vector_length
```
```
In arch/arm64/kernel/process.c (ffff800010089848)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:set_tagged_addr_ctrl
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008e7cc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_arch_ptrace
  - arch/arm64/kernel/ptrace.c:compat_arch_ptrace
  - arch/arm64/kernel/ptrace.c:sve_set
```
```
In arch/arm64/kernel/signal.c (ffff800010092020)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In arch/arm64/kernel/ssbd.c (ffff8000100ac058)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
```
```
In arch/arm64/kvm/fpsimd.c (ffff8000100dadc0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp
```
```
In kernel/fork.c (ffff8000100f467c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffff8000100fd2d8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffff80001010713c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffff80001010e4fc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffff800010da1620)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffff80001013f994)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffff80001018c820)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/module.c (ffff8000101c1824)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/module.c:flush_module_icache
  - kernel/module.c:flush_module_icache
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dc9f4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffff8000101dd91c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/auditsc.c (ffff8000101f1900)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffff800010209d48)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffff80001020ec60)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/bpf/cgroup.c (ffff80001028e0b8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffff8000102983fc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/callchain.c (ffff8000102a3a38)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffff8000102a8624)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/rseq.c (ffff8000102ac6a4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rseq.c:__arm64_sys_rseq
```
```
In mm/maccess.c (ffff8000102b9f98)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffff800010381794)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffff80001038db84)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffff8000103cfa64)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffff8000103e0b74)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffff8000104060a4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffff800010421140)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffff8000104249ec)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/proc_sysctl.c (ffff80001044a0f8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/request_key.c (ffff80001053557c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In security/integrity/iint.c (ffff8000105ac9e8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-cgroup.c (ffff80001060e31c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/tty/tty_jobctrl.c (ffff80001085fe6c)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (ffff8000108e61a0)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4be4c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:sdei_event_handler
  - drivers/firmware/arm_sdei.c:sdei_event_handler
```
```
In net/socket.c (ffff800010ba2d40)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__arm64_sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/net-sysfs.c (ffff800010c0b0bc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffff800010ca9be8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv4/ipmr.c (ffff800010ccbcb0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffff800010d00b24)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
In arch/arm/kernel/elf.c (c030ac84)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/arm/kernel/elf.c:elf_set_personality
```
```
In kernel/fork.c (c0352d64)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (c03617fc)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/signal.c (c0366608)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (c0e9974c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (c038f8a8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (c03da244)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/cgroup/cgroup-v1.c (c041ec2c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (c041f490)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/auditsc.c (c0431de0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (c0448b88)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/tracepoint.c (c044d800)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (c04d77d8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/rseq.c (c04d9cd8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rseq.c:__se_sys_rseq
```
```
In security/keys/request_key.c (c06ecb08)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (c07b8c90)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/tty/tty_jobctrl.c (c09671b0)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (c09d4804)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In net/core/net-sysfs.c (c0d22b10)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (c0db6368)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (c0e06cd4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In arch/powerpc/kernel/ptrace.c (c000000000018988)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:user_enable_block_step
  - arch/powerpc/kernel/ptrace.c:user_enable_single_step
```
```
In arch/powerpc/kernel/signal_32.c (c00000000001f154)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
```
```
In arch/powerpc/kernel/process.c (c000000000020ee4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:start_thread
```
```
In arch/powerpc/kernel/signal_64.c (c00000000003421c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
```
```
In arch/powerpc/lib/sstep.c (c0000000000b1b9c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/powerpc/lib/sstep.c:emulate_loadstore
```
```
In kernel/fork.c (c00000000013a2dc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c0000000001440fc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (c00000000014ed90)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (c000000000153d10)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sys.c (c00000000015c6a0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sys.c:__se_compat_sys_times
  - kernel/sys.c:__se_sys_times
```
```
In kernel/sched/core.c (c000000000ee26a8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (c00000000018e808)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (c0000000001e66f8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (c0000000001f3464)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/time/time.c (c0000000001fb0a4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/time/time.c:__se_sys_time32
  - kernel/time/time.c:__se_sys_time
```
```
In kernel/module.c (c00000000022cbe0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a728)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (c00000000024b62c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/auditsc.c (c000000000265bd8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (c000000000287124)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (c00000000028d2f0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/bpf/cgroup.c (c00000000033aaf8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (c0000000003427cc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/callchain.c (c000000000355e70)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (c00000000035c060)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/rseq.c (c000000000360638)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rseq.c:__se_sys_rseq
```
```
In mm/maccess.c (c000000000371f98)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (c000000000477be4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (c00000000048532c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/fcntl.c (c000000000496ecc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (c0000000004d1f78)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (c0000000004e5edc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (c00000000050ef5c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (c00000000052ffc4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (c000000000533bdc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/base.c (c0000000005516b8)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In fs/proc/proc_sysctl.c (c000000000561f60)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In ipc/shm.c (c0000000006736bc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - ipc/shm.c:__se_compat_sys_shmat
  - ipc/shm.c:__se_sys_shmat
```
```
In security/keys/request_key.c (c000000000683a44)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In security/integrity/iint.c (c00000000072aefc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-cgroup.c (c0000000007ab76c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/tty/tty_jobctrl.c (c0000000008ff420)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/char/mem.c (c000000000942624)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/base/core.c (c00000000097bde4)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/cpuidle/cpuidle-pseries.c (c000000000c2240c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
```
```
In drivers/cpuidle/cpuidle-powernv.c (c000000000c22a64)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
```
```
In net/socket.c (c000000000c76474)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/net-sysfs.c (c000000000cf484c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (c000000000dbf150)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv4/ipmr.c (c000000000de78e8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (c000000000e27edc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
In kernel/fork.c (ffffffe0000c073a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffe0000cbc88)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/signal.c (ffffffe0000d1f20)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigsuspend
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/sched/core.c (ffffffe0000e84d0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffe0000edc06)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffe000124bea)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000154820)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffe00015520c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/auditsc.c (ffffffe000165248)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffe00016bbd4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/tracepoint.c (ffffffe00016f964)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In security/keys/request_key.c (ffffffe0003953f4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
```
In block/blk-cgroup.c (ffffffe00044685c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/tty/tty_jobctrl.c (ffffffe000538046)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (ffffffe00057ac8e)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In net/core/net-sysfs.c (ffffffe0007881fa)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
```
```
In net/ipv4/devinet.c (ffffffe0008046c8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffe00084a8fe)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In arch/x86/kernel/process_64.c (ffffffff8102fc0f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff81030c91)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff81031e22)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81035533)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81a731df)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103ed60)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f947)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff8104399e)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810481a5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a73448)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077e59)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109021c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81099b26)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109fc62)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a7df8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810ad8f4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81a6e85b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d9f86)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/power/user.c (ffffffff8110959a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/rcu/tree.c (ffffffff8111ef1c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81126baf)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/stacktrace.c (ffffffff8112a8bd)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff8114e625)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161cff)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff811625a8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/auditsc.c (ffffffff81175061)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8118aa09)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffffffff8118ee5d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/bpf/cgroup.c (ffffffff811fdb38)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffff8120d4a6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff81211246)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffffffff81215318)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8121553f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff81218105)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In mm/maccess.c (ffffffff81223b6d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812d4387)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812ddcda)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff81311030)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff8131ed9a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffff8133ca89)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffff81353d8d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813575ed)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffff81375aa7)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/request_key.c (ffffffff81443d5b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In security/integrity/iint.c (ffffffff814acf6b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-cgroup.c (ffffffff815031ba)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff815c8b25)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81654167)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (ffffffff816c10f0)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a7380f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/socket.c (ffffffff818ade65)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/net-sysfs.c (ffffffff81905231)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff81993670)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv4/ipmr.c (ffffffff819af768)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff819def5c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
In arch/x86/kernel/process_64.c (ffffffff8101f62f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff810206c1)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff81021be2)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81024e73)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81a2f59f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102e560)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f147)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff81032fde)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810374b5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f7f8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107ed27)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81088568)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8108e692)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810967c4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff8109c274)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81a2ac54)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c8fb6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/power/user.c (ffffffff810fa47a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/rcu/tree.c (ffffffff8111092c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff8111960f)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/stacktrace.c (ffffffff8111d12d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff811418d5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81154f5f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff811557fe)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/auditsc.c (ffffffff81168201)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8117db33)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffffffff81181fdd)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/bpf/cgroup.c (ffffffff811f0888)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffff81200276)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff81203fd6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffffffff81208078)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8120829f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/context_tracking.c (ffffffff828ba2d2)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/context_tracking.c:context_tracking_cpu_set
```
```
In kernel/rseq.c (ffffffff8120b315)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In mm/maccess.c (ffffffff81216d1d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812c5007)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812ce95a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff81301c40)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff8130f93a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffff8132d759)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffff81344a4d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8134829d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffff81366577)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/request_key.c (ffffffff814347ab)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In security/integrity/iint.c (ffffffff8149d98b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-cgroup.c (ffffffff814f368e)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b95)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81634547)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (ffffffff8169c3a0)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2fb89)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/socket.c (ffffffff81867db5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/net-sysfs.c (ffffffff818bf061)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff8194d130)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv4/ipmr.c (ffffffff8196bd98)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff8199bd1c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
In arch/x86/kernel/process_64.c (ffffffff8102fa6f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff81030af1)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff81031c82)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81035393)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81adf5ef)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103eba0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f787)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff810437de)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047fe5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf858)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077e09)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810901cc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff81099ad6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109fc12)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a7358)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810ace54)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81adac6b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d62c6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/power/user.c (ffffffff8110748a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/rcu/tree.c (ffffffff8111ce0c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81124a9f)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/stacktrace.c (ffffffff811285dd)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff8114c4d5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115facf)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff81160378)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/auditsc.c (ffffffff81172e31)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff811887d9)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffffffff8118cc2d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/bpf/cgroup.c (ffffffff811fb908)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffff8120b246)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff8120efe6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffffffff812130b8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff812132df)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff81215ea5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In mm/maccess.c (ffffffff8122190d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812d2197)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812dbaea)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff8130ee20)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff8131c86a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffff8133a559)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffff8135185d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813550bd)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffff81373577)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/integrity/iint.c (ffffffff814a900b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-cgroup.c (ffffffff814ff24a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff815c90b5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81682527)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (ffffffff816ef5c0)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81adfc1f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/socket.c (ffffffff818fee65)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/net-sysfs.c (ffffffff81956261)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff819fdf10)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv4/ipmr.c (ffffffff81a1a008)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff81a499dc)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
In arch/x86/kernel/process_64.c (ffffffff810308bf)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff81031981)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/traps.c (ffffffff81032b48)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff810362f1)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81aebd7f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103fe40)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040a77)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/step.c (ffffffff81044bde)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810493f5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81aec028)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079ee7)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810925ac)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810a1720)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a7b82)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810af2e4)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810b5024)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81ae711d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e1c06)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/power/user.c (ffffffff8111284a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/rcu/tree.c (ffffffff8112a693)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__rcu_read_unlock
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff811310ef)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In kernel/stacktrace.c (ffffffff81134c6d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff811591bb)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116cd35)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffffffff8116d6db)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
```
In kernel/auditsc.c (ffffffff811806a3)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff81196147)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffffffff8119a5bd)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/bpf/cgroup.c (ffffffff8120a4b8)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffff8121a056)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff8121def6)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffffffff81222058)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8122227f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff812252a5)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In mm/maccess.c (ffffffff81230acd)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812e2ff7)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812ecaba)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff81320620)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff8132eb6a)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffff8134d0b9)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffff81364dfd)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8136869d)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffff813878c7)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/request_key.c (ffffffff8145709b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In security/integrity/iint.c (ffffffff814c1a1b)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-cgroup.c (ffffffff815183ca)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/idle/intel_idle.c (ffffffff815e2f15)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8169cb7c)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/base/core.c (ffffffff81709e00)
Location: include/linux/thread_info.h:53
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81aec41f)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/socket.c (ffffffff8191fe55)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/net-sysfs.c (ffffffff81978461)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff81a082a0)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv4/ipmr.c (ffffffff81a24e38)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff81a5591c)
Location: include/linux/thread_info.h:53
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
