# Function: <code>task_tgid_nr</code>

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
In kernel/exit.c (0)
Location: include/linux/sched.h:1932
Inline: True
```
```
In kernel/signal.c (ffffffff8108dd35)
Location: include/linux/sched.h:1932
Inline: True
Inline callers:
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810a5699)
Location: include/linux/sched.h:1932
Inline: True
Inline callers:
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (ffffffff8110ca12)
Location: include/linux/sched.h:1932
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup.c (0)
Location: include/linux/sched.h:1932
Inline: True
```
```
In kernel/audit.c (ffffffff811223d3)
Location: include/linux/sched.h:1932
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff811294d0)
Location: include/linux/sched.h:1932
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1932
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1932
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/sched.h:1932
Inline: True
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
In kernel/exit.c (0)
Location: include/linux/sched.h:2071
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:2071
Inline: True
```
```
In kernel/sched/core.c (ffffffff810a9cd3)
Location: include/linux/sched.h:2071
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:2071
Inline: True
```
```
In kernel/cgroup.c (0)
Location: include/linux/sched.h:2071
Inline: True
```
```
In kernel/audit.c (ffffffff8112a303)
Location: include/linux/sched.h:2071
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff8113168c)
Location: include/linux/sched.h:2071
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:2071
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:2071
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:2071
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/sched.h:2071
Inline: True
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
In kernel/exit.c (0)
Location: include/linux/sched.h:2158
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:2158
Inline: True
```
```
In kernel/sched/core.c (ffffffff810afb91)
Location: include/linux/sched.h:2158
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:2158
Inline: True
```
```
In kernel/cgroup.c (0)
Location: include/linux/sched.h:2158
Inline: True
```
```
In kernel/audit.c (ffffffff81134023)
Location: include/linux/sched.h:2158
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff8113b706)
Location: include/linux/sched.h:2158
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:2158
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:2158
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:2158
Inline: True
```
```
In security/lsm_audit.c (ffffffff813b34ed)
Location: include/linux/sched.h:2158
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/sched.h:2158
Inline: True
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
In kernel/exit.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ac341)
Location: include/linux/sched.h:1162
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In kernel/audit.c (ffffffff81135543)
Location: include/linux/sched.h:1162
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff8113cd66)
Location: include/linux/sched.h:1162
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In security/lsm_audit.c (ffffffff813c9d50)
Location: include/linux/sched.h:1162
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/sched.h:1162
Inline: True
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
In kernel/exit.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b3137)
Location: include/linux/sched.h:1162
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In kernel/audit.c (ffffffff81142283)
Location: include/linux/sched.h:1162
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff81149ae6)
Location: include/linux/sched.h:1162
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In security/lsm_audit.c (ffffffff813f01ea)
Location: include/linux/sched.h:1162
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/sched.h:1162
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/linux/sched.h:1162
Inline: True
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
In kernel/exit.c (ffffffff81091a1d)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8109db99)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810ba18c)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (ffffffff81136e82)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81146328)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
```
```
In kernel/audit.c (ffffffff81150c27)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff81155660)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
```
```
In mm/oom_kill.c (ffffffff811f3dcc)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In fs/coredump.c (ffffffff8130cbd7)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8131de44)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In security/lsm_audit.c (ffffffff81420d7b)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff8161d072)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8165b7bc)
Location: include/linux/sched.h:1254
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff81099cfd)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810a6599)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810c328c)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (ffffffff81142602)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151ecc)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
```
```
In kernel/audit.c (ffffffff8115d8c7)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff81162a10)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_set_loginuid
```
```
In mm/oom_kill.c (ffffffff81205c0f)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (ffffffff8132203a)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8133522e)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In security/lsm_audit.c (ffffffff8143d5b4)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff8163a2d2)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81676028)
Location: include/linux/sched.h:1256
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff8109e30c)
Location: include/linux/sched.h:1328
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810ab28d)
Location: include/linux/sched.h:1328
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810c9325)
Location: include/linux/sched.h:1328
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (ffffffff8114da22)
Location: include/linux/sched.h:1328
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115dc40)
Location: include/linux/sched.h:1328
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff8116b6ac)
Location: include/linux/sched.h:1328
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff8116e897)
Location: include/linux/sched.h:1328
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (ffffffff8121c218)
Location: include/linux/sched.h:1328
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (ffffffff81349576)
Location: include/linux/sched.h:1328
Inline: True
```
```
In fs/proc/base.c (ffffffff8135cd7f)
Location: include/linux/sched.h:1328
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In security/lsm_audit.c (ffffffff8146b146)
Location: include/linux/sched.h:1328
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff8166e5fa)
Location: include/linux/sched.h:1328
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816abe38)
Location: include/linux/sched.h:1328
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff810a63b3)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b1896)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810d23f5)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (ffffffff81159732)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81169850)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff8117758c)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff8117a717)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (ffffffff81229be4)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (ffffffff81361816)
Location: include/linux/sched.h:1322
Inline: True
```
```
In fs/proc/base.c (ffffffff813754ef)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In security/lsm_audit.c (ffffffff81484f26)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff81690c3a)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816cebb8)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff810ae177)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b9ea6)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810dc32d)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/kexec_core.c (ffffffff8116aae2)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117b3ce)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff8118a1fe)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff8118d739)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (ffffffff81256a41)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (ffffffff813a77d3)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
```
```
In fs/proc/base.c (ffffffff813bdf6b)
Location: include/linux/sched.h:1363
Inline: True
```
```
In security/lsm_audit.c (ffffffff814dad94)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff8174372a)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81783ab8)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff810a982a)
Location: include/linux/sched.h:1422
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b5156)
Location: include/linux/sched.h:1422
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810d8b3d)
Location: include/linux/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/kexec_core.c (ffffffff81167222)
Location: include/linux/sched.h:1422
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81be478d)
Location: include/linux/sched.h:1422
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff81187523)
Location: include/linux/sched.h:1422
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff8118a8d9)
Location: include/linux/sched.h:1422
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (ffffffff812615df)
Location: include/linux/sched.h:1422
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (ffffffff813b88ed)
Location: include/linux/sched.h:1422
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
```
```
In fs/proc/base.c (ffffffff813cfcbb)
Location: include/linux/sched.h:1422
Inline: True
```
```
In security/lsm_audit.c (ffffffff814f81fa)
Location: include/linux/sched.h:1422
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff8175f5aa)
Location: include/linux/sched.h:1422
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81c0a358)
Location: include/linux/sched.h:1422
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff810aa85c)
Location: include/linux/sched.h:1444
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b6d46)
Location: include/linux/sched.h:1444
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810da4ad)
Location: include/linux/sched.h:1444
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/kexec_core.c (ffffffff81167fb2)
Location: include/linux/sched.h:1444
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81bd65b6)
Location: include/linux/sched.h:1444
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff81188593)
Location: include/linux/sched.h:1444
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff8118b785)
Location: include/linux/sched.h:1444
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (ffffffff81265e1f)
Location: include/linux/sched.h:1444
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (ffffffff813bf92d)
Location: include/linux/sched.h:1444
Inline: True
```
```
In fs/proc/base.c (ffffffff813d6b9b)
Location: include/linux/sched.h:1444
Inline: True
```
```
In security/lsm_audit.c (ffffffff814fef3a)
Location: include/linux/sched.h:1444
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff8174341a)
Location: include/linux/sched.h:1444
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81bfbdeb)
Location: include/linux/sched.h:1444
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff810bc383)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810c7259)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810ede2d)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/kexec_core.c (ffffffff8118d997)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81cb31bb)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff811b0ab3)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff811b43b5)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (ffffffff812a3700)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (ffffffff8140f75d)
Location: include/linux/sched.h:1542
Inline: True
```
```
In fs/proc/base.c (ffffffff814282da)
Location: include/linux/sched.h:1542
Inline: True
```
```
In security/lsm_audit.c (ffffffff81559f94)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff817c3eba)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81cfca75)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff810d2e71)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810df67b)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff8110a31a)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/kexec_core.c (ffffffff811bce87)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81e63fc1)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff811e2cc6)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff811e68f7)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_log_uring
```
```
In mm/oom_kill.c (ffffffff812fb651)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_badness
```
```
In fs/coredump.c (ffffffff81485363)
Location: include/linux/sched.h:1554
Inline: True
```
```
In fs/proc/base.c (ffffffff814a1517)
Location: include/linux/sched.h:1554
Inline: True
```
```
In security/lsm_audit.c (ffffffff815f4c7f)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff8190074a)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81ec5252)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff810f19b1)
Location: include/linux/sched.h:1576
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810ff9f7)
Location: include/linux/sched.h:1576
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff8112efe7)
Location: include/linux/sched.h:1576
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/kexec_core.c (ffffffff811fee37)
Location: include/linux/sched.h:1576
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812146c3)
Location: include/linux/sched.h:1576
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff81228bb6)
Location: include/linux/sched.h:1576
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff8122c387)
Location: include/linux/sched.h:1576
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_log_uring
```
```
In kernel/trace/bpf_trace.c (ffffffff812a6c26)
Location: include/linux/sched.h:1576
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In mm/oom_kill.c (ffffffff813656fb)
Location: include/linux/sched.h:1576
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_badness
```
```
In fs/coredump.c (ffffffff8151872a)
Location: include/linux/sched.h:1576
Inline: True
```
```
In fs/proc/base.c (ffffffff81536537)
Location: include/linux/sched.h:1576
Inline: True
```
```
In security/lsm_audit.c (ffffffff816a574f)
Location: include/linux/sched.h:1576
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff81a5a35a)
Location: include/linux/sched.h:1576
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81aa5b4c)
Location: include/linux/sched.h:1576
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff810fd934)
Location: include/linux/sched.h:1585
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8110ba3a)
Location: include/linux/sched.h:1585
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff8113c8b7)
Location: include/linux/sched.h:1585
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/kexec_core.c (ffffffff81214237)
Location: include/linux/sched.h:1585
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81229fe3)
Location: include/linux/sched.h:1585
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff8123f1b6)
Location: include/linux/sched.h:1585
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff81242a47)
Location: include/linux/sched.h:1585
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_log_uring
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8ce6)
Location: include/linux/sched.h:1585
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In mm/oom_kill.c (ffffffff81397b9e)
Location: include/linux/sched.h:1585
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_badness
```
```
In fs/coredump.c (ffffffff8154ffde)
Location: include/linux/sched.h:1585
Inline: True
```
```
In fs/proc/base.c (ffffffff8156e6f7)
Location: include/linux/sched.h:1585
Inline: True
```
```
In security/lsm_audit.c (ffffffff816de1f6)
Location: include/linux/sched.h:1585
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff81aa498a)
Location: include/linux/sched.h:1585
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81af134c)
Location: include/linux/sched.h:1585
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff811067af)
Location: include/linux/pid.h:244
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff811153ea)
Location: include/linux/pid.h:244
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff81147947)
Location: include/linux/pid.h:244
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/kexec_core.c (ffffffff8122c187)
Location: include/linux/pid.h:244
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81241e83)
Location: include/linux/pid.h:244
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff81259026)
Location: include/linux/pid.h:244
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff8125c9c7)
Location: include/linux/pid.h:244
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:audit_log_uring
```
```
In kernel/trace/bpf_trace.c (ffffffff812e5cb6)
Location: include/linux/pid.h:244
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In mm/oom_kill.c (ffffffff813c19cc)
Location: include/linux/pid.h:244
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_badness
```
```
In fs/coredump.c (ffffffff81585e3e)
Location: include/linux/pid.h:244
Inline: True
```
```
In fs/proc/base.c (ffffffff815a70b7)
Location: include/linux/pid.h:244
Inline: True
```
```
In security/lsm_audit.c (ffffffff8171adb6)
Location: include/linux/pid.h:244
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff81af738a)
Location: include/linux/pid.h:244
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81b448ac)
Location: include/linux/pid.h:244
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In virt/kvm/arm/arm.c (ffff8000100c8104)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_init
```
```
In arch/arm64/kvm/handle_exit.c (ffff8000100d1904)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - arch/arm64/kvm/handle_exit.c:handle_exit
  - arch/arm64/kvm/handle_exit.c:kvm_handle_unknown_ec
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100da2ec)
Location: include/linux/sched.h:1322
Inline: True
```
```
In kernel/exit.c (ffff8000100fd348)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffff80001010d53c)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffff800010132934)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (ffff8000101c8d48)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dc6b0)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffff8000101ec5a0)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffff8000101ef8a4)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (ffff8000102b79c8)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (ffff800010427efc)
Location: include/linux/sched.h:1322
Inline: True
```
```
In fs/proc/base.c (ffff80001043f678)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In security/lsm_audit.c (ffff8000105772b4)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffff800010864208)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffff8000108b8fdc)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (c035a460)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (c0365880)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (c0380c40)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (c040fbc0)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (c041e964)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (c042c208)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (c042fcec)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (c04e4658)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
```
```
In fs/coredump.c (c05f0dec)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
```
```
In fs/proc/base.c (c06060b8)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In security/lsm_audit.c (c0729e58)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (c0969dec)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (c09b25a4)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In arch/powerpc/kernel/traps.c (c00000000002d818)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:die_will_crash
```
```
In kernel/exit.c (c000000000144194)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (c000000000154718)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (c00000000017cd9c)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (c000000000231498)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a370)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (c00000000025e02c)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (c0000000002624d0)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (c00000000036f810)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (c00000000053813c)
Location: include/linux/sched.h:1322
Inline: True
```
```
In fs/proc/base.c (c000000000554bac)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In security/lsm_audit.c (c0000000006e056c)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (c000000000902bb0)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (c000000000959d88)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffe0000c5bda)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffe0000ce79a)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffe0000e4d20)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe00015462e)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffe000160c2c)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffe0001635b2)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (ffffffe0001dbc94)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
```
```
In fs/coredump.c (ffffffe0002c64f0)
Location: include/linux/sched.h:1322
Inline: True
```
```
In fs/proc/base.c (ffffffe0002d7326)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In security/lsm_audit.c (ffffffe0003c95aa)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffe00053a5ac)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffe000569538)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff8109fcd3)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810abc06)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810cc775)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (ffffffff81151d52)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161e70)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff8116fbac)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff81172d37)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (ffffffff81222234)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (ffffffff81359df6)
Location: include/linux/sched.h:1322
Inline: True
```
```
In fs/proc/base.c (ffffffff8136dacf)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In security/lsm_audit.c (ffffffff8147d506)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff816566ba)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81694608)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff8108e703)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8109a596)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810baf75)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (ffffffff81145032)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811550d0)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff81162d4c)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff81165ed7)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (ffffffff812153e4)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (ffffffff8134aaa6)
Location: include/linux/sched.h:1322
Inline: True
```
```
In fs/proc/base.c (ffffffff8135e55f)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In security/lsm_audit.c (ffffffff8146df26)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff81636a4a)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81671ff8)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff8109fc83)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810ab166)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810cbc95)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (ffffffff8114fc02)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115fc40)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff8116d97c)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff81170b07)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (ffffffff8121ffd4)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (ffffffff813578c6)
Location: include/linux/sched.h:1322
Inline: True
```
```
In fs/proc/base.c (ffffffff8136b59f)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In security/lsm_audit.c (ffffffff814795a6)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff81684a7a)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816c2878)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
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
In kernel/exit.c (ffffffff810a7bf3)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b3246)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:unhandled_signal
```
```
In kernel/sched/core.c (ffffffff810d41f5)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/kexec_core.c (ffffffff8115ca62)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116cf64)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
```
In kernel/audit.c (ffffffff8117b165)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
```
```
In kernel/auditsc.c (ffffffff8117e317)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
```
In mm/oom_kill.c (ffffffff8122f0cf)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/coredump.c (ffffffff8136afa6)
Location: include/linux/sched.h:1322
Inline: True
```
```
In fs/proc/base.c (ffffffff8137ecf9)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In security/lsm_audit.c (ffffffff81491056)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/tty/sysrq.c (ffffffff8169f08a)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816dce48)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
</details>
</li>
</ul>

## Differences
