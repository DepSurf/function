# Function: <code>set_tsk_thread_flag</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102de62)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff8102f3a8)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81039442)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103dc48)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In kernel/fork.c (ffffffff8107f22a)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff8108b570)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff8108d139)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - kernel/signal.c:recalc_sigpending_tsk
  - kernel/signal.c:signal_wake_up_state
```
```
In kernel/sched/core.c (ffffffff810aa379)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/cgroup.c (ffffffff8111793c)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/auditsc.c (ffffffff811282e4)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8113b8b3)
Location: include/linux/sched.h:2854
Inline: True
```
```
In kernel/tracepoint.c (ffffffff8113fc72)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff81188b57)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811897a2)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In block/blk-cgroup.c (ffffffff813d90a4)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff81547db0)
Location: include/linux/sched.h:2854
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81736b8f)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
```
In net/ipv4/devinet.c (ffffffff81792e27)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff817cd3b3)
Location: include/linux/sched.h:2854
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
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
In arch/x86/kernel/process_64.c (ffffffff8102cd84)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff8102e3cc)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103844b)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103db17)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff810813e0)
Location: include/linux/sched.h:3131
Inline: True
```
```
In kernel/ptrace.c (ffffffff8108e570)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81090dfd)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff810acfd3)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/cgroup.c (ffffffff8111f9a3)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/auditsc.c (ffffffff8113048b)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff811443db)
Location: include/linux/sched.h:3131
Inline: True
```
```
In kernel/tracepoint.c (ffffffff811482d2)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff8119b227)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8119be82)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In block/blk-cgroup.c (ffffffff8141ee1f)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff81599a10)
Location: include/linux/sched.h:3131
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff817a2d5c)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
```
In net/ipv4/devinet.c (ffffffff818005dd)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8183aaa6)
Location: include/linux/sched.h:3131
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In arch/x86/kernel/process_64.c (ffffffff8102ce3e)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff8102e324)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81037ed4)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103d3f3)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff81085e41)
Location: include/linux/sched.h:3287
Inline: True
```
```
In kernel/ptrace.c (ffffffff810931c0)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81095d7d)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff810b305f)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810cd809)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/cgroup.c (ffffffff81127f4d)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/auditsc.c (ffffffff8113a1f7)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8114e28f)
Location: include/linux/sched.h:3287
Inline: True
```
```
In kernel/tracepoint.c (ffffffff81152194)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff811aac2b)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811ab862)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In block/blk-cgroup.c (ffffffff8143a3df)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff815c7ce0)
Location: include/linux/sched.h:3287
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff817d17bc)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
```
In net/ipv4/devinet.c (ffffffff8183153d)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8186c4a6)
Location: include/linux/sched.h:3287
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In arch/x86/kernel/process_64.c (ffffffff8102b03e)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff8102c427)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81035fac)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103b443)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff8108282e)
Location: include/linux/sched.h:1482
Inline: True
```
```
In kernel/ptrace.c (ffffffff81090238)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81092d2d)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff810aef3c)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810ca229)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/livepatch/transition.c (ffffffff810f90af)
Location: include/linux/sched.h:1482
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112ac2b)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/auditsc.c (ffffffff8113b837)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8115093b)
Location: include/linux/sched.h:1482
Inline: True
```
```
In kernel/tracepoint.c (ffffffff81154774)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff811b214c)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811b2cc2)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In block/blk-cgroup.c (ffffffff81447b51)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff815dc970)
Location: include/linux/sched.h:1482
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff817f0ba8)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
```
In net/ipv4/devinet.c (ffffffff81852ae6)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8188e48e)
Location: include/linux/sched.h:1482
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102bd69)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff8102d327)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103830c)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103de5f)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff8108966a)
Location: include/linux/sched.h:1516
Inline: True
```
```
In kernel/ptrace.c (ffffffff810970a8)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81099c0d)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff810b6192)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d1a09)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/livepatch/transition.c (ffffffff81103aaf)
Location: include/linux/sched.h:1516
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811379c1)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/auditsc.c (ffffffff81148596)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8115cb75)
Location: include/linux/sched.h:1516
Inline: True
```
```
In kernel/tracepoint.c (ffffffff81160f94)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff811c5d5c)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811c6912)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In block/blk-cgroup.c (ffffffff81474751)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff816439b0)
Location: include/linux/sched.h:1516
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff8186c1af)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff818d28f6)
Location: include/linux/sched.h:1516
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8190f9ee)
Location: include/linux/sched.h:1516
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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102cd80)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff8102e349)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103977d)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103f3ff)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In kernel/fork.c (ffffffff8108d56e)
Location: include/linux/sched.h:1632
Inline: True
```
```
In kernel/ptrace.c (ffffffff8109a59a)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff8109dbd5)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff819ec5ec)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c40c6)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/livepatch/transition.c (ffffffff8110c391)
Location: include/linux/sched.h:1632
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8114626d)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/auditsc.c (ffffffff81156f66)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8116bf29)
Location: include/linux/sched.h:1632
Inline: True
```
```
In kernel/tracepoint.c (ffffffff8116fee4)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff811e6238)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811e6e4f)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff811ea05e)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In block/blk-cgroup.c (ffffffff814a8864)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff8167ed60)
Location: include/linux/sched.h:1632
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff818bca91)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff81928e9f)
Location: include/linux/sched.h:1632
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81967243)
Location: include/linux/sched.h:1632
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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102dfd0)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff8102f609)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103aad4)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff810409ff)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81044e65)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In kernel/fork.c (ffffffff810956c8)
Location: include/linux/sched.h:1645
Inline: True
```
```
In kernel/ptrace.c (ffffffff810a27da)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810a5ee5)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81a2786e)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810cd3c6)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff81114a65)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/livepatch/transition.c (ffffffff81117b81)
Location: include/linux/sched.h:1645
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151e13)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/auditsc.c (ffffffff81163fb6)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8117993f)
Location: include/linux/sched.h:1645
Inline: True
```
```
In kernel/tracepoint.c (ffffffff8117da94)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff811f6d88)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff811f7a7f)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff811fabce)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In block/blk-cgroup.c (ffffffff814c2e1f)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff8169f1a0)
Location: include/linux/sched.h:1645
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff818e3d41)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff8195818f)
Location: include/linux/sched.h:1645
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8199c713)
Location: include/linux/sched.h:1645
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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fd37)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff81031402)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103d09c)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e1a1)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
```
```
In arch/x86/kernel/step.c (ffffffff810430be)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810477f5)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In kernel/fork.c (ffffffff81099878)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff810a7460)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810aabb5)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81a98115)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d5786)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8111a53c)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81121faf)
Location: include/linux/sched.h:1718
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115dacf)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/auditsc.c (ffffffff81170bc1)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff811863cd)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/tracepoint.c (ffffffff8118a92d)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff8120eb4e)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8120f8bf)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff812122d5)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff81431a1b)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff814f159f)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff816d77e0)
Location: include/linux/sched.h:1718
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81932721)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff819bcbe0)
Location: include/linux/sched.h:1718
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81a0898c)
Location: include/linux/sched.h:1718
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
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030697)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff81031cc2)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103d85c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e961)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
```
```
In arch/x86/kernel/step.c (ffffffff8104381e)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048035)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In kernel/fork.c (ffffffff810a0206)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff810ada88)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810b11b5)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81acf9eb)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810dfd96)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8112693c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff8112e5cf)
Location: include/linux/sched.h:1711
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811696df)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/auditsc.c (ffffffff8117ca41)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff811923e9)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffffffff8119683d)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff8121c18e)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8121ceef)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff8121fab5)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff8144b77b)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff8150abda)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff816fb900)
Location: include/linux/sched.h:1711
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81965261)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff819f38d0)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81a3f8cc)
Location: include/linux/sched.h:1711
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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810344b0)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81037107)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff81040ac0)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81041c35)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
```
```
In arch/x86/kernel/step.c (ffffffff810471ae)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c106)
Location: include/linux/sched.h:1761
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
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In kernel/fork.c (ffffffff810a6cc8)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_seccomp
```
```
In kernel/ptrace.c (ffffffff810b54a8)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810bc500)
Location: include/linux/sched.h:1761
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
In kernel/sched/core.c (ffffffff810dde4b)
Location: include/linux/sched.h:1761
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
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff81136cba)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_sched_exp_online_cleanup
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff8113ce4c)
Location: include/linux/sched.h:1761
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117b362)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/auditsc.c (ffffffff8118f660)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff811a72ad)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_strict
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/tracepoint.c (ffffffff811abb6d)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff8124881e)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8124926f)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff8124bda3)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff8149d786)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff8156bbab)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff817b6248)
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81a3868e)
Location: include/linux/sched.h:1761
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
Location: include/linux/sched.h:1761
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81b34a3a)
Location: include/linux/sched.h:1761
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
In arch/x86/kernel/ioport.c (ffffffff810381c7)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff81040a19)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81041c86)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
```
```
In arch/x86/kernel/step.c (ffffffff810469fe)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b63e)
Location: include/linux/sched.h:1822
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
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In kernel/signal.c (ffffffff810b77f0)
Location: include/linux/sched.h:1822
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
Location: include/linux/sched.h:1822
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
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/sched/membarrier.c (ffffffff81108feb)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff8113231a)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_sched_exp_online_cleanup
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81be33f7)
Location: include/linux/sched.h:1822
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178237)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/events/uprobes.c (ffffffff81252f2e)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff812537ef)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff81256239)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff814bb2a6)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff815868f2)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff817cb6b8)
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81a3b8cc)
Location: include/linux/sched.h:1822
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
Location: include/linux/sched.h:1822
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81b4351a)
Location: include/linux/sched.h:1822
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
In arch/x86/kernel/ioport.c (ffffffff81039d07)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff81042411)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81043686)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
```
```
In arch/x86/kernel/step.c (ffffffff810482fc)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d2ee)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ec9b)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In kernel/signal.c (ffffffff810b8d60)
Location: include/linux/sched.h:1844
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
Location: include/linux/sched.h:1844
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
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/sched/membarrier.c (ffffffff8110b09b)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff81bd48d4)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81bd5343)
Location: include/linux/sched.h:1844
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178daa)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/events/uprobes.c (ffffffff8125726e)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff81257e0f)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff8125a80b)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff814c1166)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff8158d602)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff817af028)
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81a22d3e)
Location: include/linux/sched.h:1844
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
Location: include/linux/sched.h:1844
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81b31baa)
Location: include/linux/sched.h:1844
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
In arch/x86/kernel/ioport.c (ffffffff8103f6b7)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff8104875e)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104989b)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/step.c (ffffffff8104ec0e)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054a1e)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81056d0b)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In kernel/signal.c (ffffffff810cb2f0)
Location: include/linux/sched.h:1961
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
Location: include/linux/sched.h:1961
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
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/sched/membarrier.c (ffffffff811298fb)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff81caed4c)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81cb0052)
Location: include/linux/sched.h:1961
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811a06da)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/events/uprobes.c (ffffffff81292ffe)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8129397f)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff812965fb)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff81519bd6)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff815f30a6)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff81838244)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81ad72d5)
Location: include/linux/sched.h:1961
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
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81bf907a)
Location: include/linux/sched.h:1961
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81046d16)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff81051a50)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81053459)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/step.c (ffffffff81059d9c)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810600df)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In kernel/signal.c (ffffffff810e493f)
Location: include/linux/sched.h:1983
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
Location: include/linux/sched.h:1983
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
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:idle_inject_timer_fn
```
```
In kernel/sched/build_utility.c (ffffffff8113eeab)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff8117dbe0)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_flavor_sched_clock_irq
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81e60c69)
Location: include/linux/sched.h:1983
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0e37)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/events/uprobes.c (ffffffff812e8a6b)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff812e945f)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff812ec5b1)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff815ac856)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff816a454b)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff8197a5b8)
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81c579f1)
Location: include/linux/sched.h:1983
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
Location: include/linux/sched.h:1983
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81d92459)
Location: include/linux/sched.h:1983
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81050e46)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff8105f0cc)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81060d87)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/step.c (ffffffff8106795c)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106e7d3)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In kernel/signal.c (ffffffff81104fbf)
Location: include/linux/sched.h:2010
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
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff8113461b)
Location: include/linux/sched.h:2010
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
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:idle_inject_timer_fn
```
```
In kernel/sched/build_utility.c (ffffffff811692fb)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff811b6a84)
Location: include/linux/sched.h:2010
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
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_start_transition
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81214997)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/events/uprobes.c (ffffffff813527cb)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff813531df)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff813568e1)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff81656d46)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff81763239)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff81ae7418)
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81e0d7b1)
Location: include/linux/sched.h:2010
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
Location: include/linux/sched.h:2010
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81f60b79)
Location: include/linux/sched.h:2010
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
In arch/x86/kernel/ioport.c (ffffffff81051b76)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff810607cc)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81062787)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/step.c (ffffffff8106920c)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106ffb3)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In kernel/signal.c (ffffffff8111123f)
Location: include/linux/sched.h:2018
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
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff811524a6)
Location: include/linux/sched.h:2018
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
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:idle_inject_timer_fn
```
```
In kernel/sched/build_utility.c (ffffffff811799fb)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff811c74b4)
Location: include/linux/sched.h:2018
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
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_start_transition
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a2b7)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/events/uprobes.c (ffffffff813839db)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff813843df)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff8138807c)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff8168f67f)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff817a1d63)
Location: include/linux/sched.h:2018
Inline: True
```
```
In drivers/base/core.c (ffffffff81b35848)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81e80a01)
Location: include/linux/sched.h:2018
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
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81fc09a9)
Location: include/linux/sched.h:2018
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
In arch/x86/kernel/ioport.c (ffffffff81058d96)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/process.c (ffffffff81067877)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810698b0)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/step.c (ffffffff8107067c)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810777d3)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In kernel/signal.c (ffffffff8111abbe)
Location: include/linux/sched.h:1920
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
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff8115e36b)
Location: include/linux/sched.h:1920
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
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:idle_inject_timer_fn
```
```
In kernel/sched/build_utility.c (ffffffff8118742b)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
```
```
In kernel/rcu/tree.c (ffffffff811d79d4)
Location: include/linux/sched.h:1920
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
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_start_transition
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81242157)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/events/uprobes.c (ffffffff813ace3b)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff813ad7ef)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff813b1adc)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff816cbc0f)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff817e58b0)
Location: include/linux/sched.h:1920
Inline: True
```
```
In drivers/base/core.c (ffffffff81b8d268)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81f419be)
Location: include/linux/sched.h:1920
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
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8208de6a)
Location: include/linux/sched.h:1920
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
In arch/arm64/kernel/fpsimd.c (ffff8000100881e8)
Location: include/linux/sched.h:1711
Inline: True
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008d3d8)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:sve_set
```
```
In arch/arm64/kernel/ssbd.c (ffff8000100ac058)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
```
```
In kernel/fork.c (ffff8000100f467c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffff80001010713c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffff80001010cdc4)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffff800010da1620)
Location: include/linux/sched.h:1711
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
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffff80001018c820)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dc9f4)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/auditsc.c (ffff8000101f1900)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffff800010209d48)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffff80001020ec60)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffff8000102a7b18)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/rseq.c (ffff8000102ac6a4)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rseq.c:__arm64_sys_rseq
```
```
In security/keys/request_key.c (ffff80001053557c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffff80001060e31c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffff8000108e61a0)
Location: include/linux/sched.h:1711
Inline: True
```
```
In net/core/net-sysfs.c (ffff800010c0b0bc)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffff800010ca9be8)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffff800010d00b24)
Location: include/linux/sched.h:1711
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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0352d64)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (c03617fc)
Location: include/linux/sched.h:1711
Inline: True
```
```
In kernel/signal.c (c0365038)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (c0e9974c)
Location: include/linux/sched.h:1711
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
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (c03da244)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/cgroup/cgroup-v1.c (c041ec2c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/auditsc.c (c0431de0)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (c0448b88)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/tracepoint.c (c044d800)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (c04d6c20)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/rseq.c (c04d9cd8)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rseq.c:__se_sys_rseq
```
```
In security/keys/request_key.c (c06ecb08)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (c07b8c90)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (c09d4804)
Location: include/linux/sched.h:1711
Inline: True
```
```
In net/core/net-sysfs.c (c0d22b10)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (c0db6368)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (c0e06cd4)
Location: include/linux/sched.h:1711
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
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:user_enable_block_step
  - arch/powerpc/kernel/ptrace.c:user_enable_single_step
```
```
In kernel/fork.c (c00000000013a2dc)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (c00000000014ed90)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (c000000000153d10)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (c000000000ee26a8)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (c00000000018e808)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (c0000000001e66f8)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (c0000000001f3464)
Location: include/linux/sched.h:1711
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a728)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/auditsc.c (c000000000265bd8)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (c000000000287124)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (c00000000028d2f0)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (c00000000035b1dc)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/rseq.c (c000000000360638)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rseq.c:__se_sys_rseq
```
```
In security/keys/request_key.c (c000000000683a44)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (c0000000007ab76c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (c00000000097bde4)
Location: include/linux/sched.h:1711
Inline: True
```
```
In net/core/net-sysfs.c (c000000000cf484c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (c000000000dbf150)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (c000000000e27edc)
Location: include/linux/sched.h:1711
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c073a)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffe0000cbc88)
Location: include/linux/sched.h:1711
Inline: True
```
```
In kernel/signal.c (ffffffe0000cfaa4)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/sched/core.c (ffffffe0000e84d0)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffe0000edc06)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffe000124bea)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000154820)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/auditsc.c (ffffffe000165248)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffe00016bbd4)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/tracepoint.c (ffffffe00016f964)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In security/keys/request_key.c (ffffffe0003953f4)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
```
```
In block/blk-cgroup.c (ffffffe00044685c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffe00057ac8e)
Location: include/linux/sched.h:1711
Inline: True
```
```
In net/core/net-sysfs.c (ffffffe0007881fa)
Location: include/linux/sched.h:1711
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
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffe00084a8fe)
Location: include/linux/sched.h:1711
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
In arch/x86/kernel/process_64.c (ffffffff810307f7)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff81031e22)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103d9dc)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103eae1)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
```
```
In arch/x86/kernel/step.c (ffffffff8104399e)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810481a5)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In kernel/fork.c (ffffffff81099b26)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff810a7df8)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810ab525)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81a6e85b)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d9f86)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8111ef1c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81126baf)
Location: include/linux/sched.h:1711
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161cff)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/auditsc.c (ffffffff81175061)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8118aa09)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffffffff8118ee5d)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff812147de)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8121553f)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff81218105)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff81443d5b)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff815031ba)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff816c10f0)
Location: include/linux/sched.h:1711
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81905231)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff81993670)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff819def5c)
Location: include/linux/sched.h:1711
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
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81020287)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff81021be2)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8102d0ce)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102e2e1)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
```
```
In arch/x86/kernel/step.c (ffffffff81032fde)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810374b5)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In kernel/fork.c (ffffffff81088568)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff810967c4)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81099ec5)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81a2ac54)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c8fb6)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8111092c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff8111960f)
Location: include/linux/sched.h:1711
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81154f5f)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/auditsc.c (ffffffff81168201)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff8117db33)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffffffff81181fdd)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff81207548)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8120829f)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/context_tracking.c (ffffffff828ba2d2)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/context_tracking.c:context_tracking_cpu_set
```
```
In kernel/rseq.c (ffffffff8120b315)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff814347ab)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff814f368e)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff8169c3a0)
Location: include/linux/sched.h:1711
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff818bf061)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff8194d130)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8199bd1c)
Location: include/linux/sched.h:1711
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
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030657)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff81031c82)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103d81c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e921)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
```
```
In arch/x86/kernel/step.c (ffffffff810437de)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047fe5)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In kernel/fork.c (ffffffff81099ad6)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff810a7358)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810aaa85)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81adac6b)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d62c6)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8111ce0c)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/transition.c (ffffffff81124a9f)
Location: include/linux/sched.h:1711
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115facf)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/auditsc.c (ffffffff81172e31)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff811887d9)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffffffff8118cc2d)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff8121257e)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff812132df)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff81215ea5)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In block/blk-cgroup.c (ffffffff814ff24a)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff816ef5c0)
Location: include/linux/sched.h:1711
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81956261)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff819fdf10)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81a499dc)
Location: include/linux/sched.h:1711
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
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810314e7)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/traps.c (ffffffff81032b48)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff8103e96a)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103fb55)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
```
```
In arch/x86/kernel/step.c (ffffffff81044bde)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810493f5)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
```
In kernel/fork.c (ffffffff810a1720)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff810af2e4)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810b2b65)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sched/core.c (ffffffff81ae711d)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e1c06)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8112a693)
Location: include/linux/sched.h:1711
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
Location: include/linux/sched.h:1711
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116cd35)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/auditsc.c (ffffffff811806a3)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffffffff81196147)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffffffff8119a5bd)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/events/uprobes.c (ffffffff812214f5)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In kernel/user-return-notifier.c (ffffffff8122227f)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/rseq.c (ffffffff812252a5)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
```
In security/keys/request_key.c (ffffffff8145709b)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - security/keys/request_key.c:cache_requested_key
```
```
In block/blk-cgroup.c (ffffffff815183ca)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff81709e00)
Location: include/linux/sched.h:1711
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81978461)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff81a082a0)
Location: include/linux/sched.h:1711
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81a5591c)
Location: include/linux/sched.h:1711
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

## Differences
