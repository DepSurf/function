# Function: <code>task_tgid_nr_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pid_t task_tgid_nr_ns(struct task_struct *tsk, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109dcf0)
Location: kernel/pid.c:539
Inline: False
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/auditsc.c:audit_filter_rules
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_mmap_output
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/self.c:proc_self_readlink
  - fs/proc/self.c:proc_self_follow_link
  - fs/proc/thread_self.c:proc_thread_self_readlink
  - fs/proc/thread_self.c:proc_thread_self_follow_link
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
**Symbols:**

```
ffffffff8109dcf0-ffffffff8109dd31: task_tgid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pid_t task_tgid_nr_ns(struct task_struct *tsk, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1350)
Location: kernel/pid.c:539
Inline: False
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/self.c:proc_self_readlink
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_readlink
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
**Symbols:**

```
ffffffff810a1350-ffffffff810a1391: task_tgid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pid_t task_tgid_nr_ns(struct task_struct *tsk, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6410)
Location: kernel/pid.c:539
Inline: False
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
**Symbols:**

```
ffffffff810a6410-ffffffff810a6451: task_tgid_nr_ns (STB_GLOBAL)
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
In kernel/signal.c (ffffffff81093a01)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff8111c7fe)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff81135bcb)
Location: include/linux/sched.h:1203
Inline: True
```
```
In kernel/auditsc.c (ffffffff8113a694)
Location: include/linux/sched.h:1203
Inline: True
```
```
In kernel/taskstats.c (ffffffff81153868)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81153cac)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff811a063d)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
```
```
In fs/proc/array.c (ffffffff812cfb66)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/self.c (ffffffff812d3707)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff812d38e5)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff8138b12d)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff813d60b7)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff8109a8f3)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff81127f1e)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff8114290b)
Location: include/linux/sched.h:1203
Inline: True
```
```
In kernel/auditsc.c (ffffffff81147360)
Location: include/linux/sched.h:1203
Inline: True
```
```
In kernel/taskstats.c (ffffffff81160068)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811604ac)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (ffffffff812f42e5)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/self.c (ffffffff812f7f37)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff812f8115)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff813b04ad)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff813fc5d7)
Location: include/linux/sched.h:1203
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff8109e8c5)
Location: include/linux/sched.h:1295
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff81135d18)
Location: include/linux/sched.h:1295
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff811512fd)
Location: include/linux/sched.h:1295
Inline: True
```
```
In kernel/auditsc.c (ffffffff81155d1a)
Location: include/linux/sched.h:1295
Inline: True
```
```
In kernel/taskstats.c (ffffffff8116efa4)
Location: include/linux/sched.h:1295
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8116f3da)
Location: include/linux/sched.h:1295
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (ffffffff81321705)
Location: include/linux/sched.h:1295
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/self.c (ffffffff8132527f)
Location: include/linux/sched.h:1295
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81325451)
Location: include/linux/sched.h:1295
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff813e051f)
Location: include/linux/sched.h:1295
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff8142d53a)
Location: include/linux/sched.h:1295
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff810a6b9d)
Location: include/linux/sched.h:1297
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff811414a8)
Location: include/linux/sched.h:1297
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff8115dfa7)
Location: include/linux/sched.h:1297
Inline: True
```
```
In kernel/auditsc.c (ffffffff811630af)
Location: include/linux/sched.h:1297
Inline: True
```
```
In kernel/taskstats.c (ffffffff8117caa4)
Location: include/linux/sched.h:1297
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8117ceda)
Location: include/linux/sched.h:1297
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (ffffffff81338815)
Location: include/linux/sched.h:1297
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/self.c (ffffffff8133c41f)
Location: include/linux/sched.h:1297
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff8133c5f1)
Location: include/linux/sched.h:1297
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff813fad1d)
Location: include/linux/sched.h:1297
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff81449e8a)
Location: include/linux/sched.h:1297
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff810ab81c)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff8114c8a0)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff8116a2e0)
Location: include/linux/sched.h:1369
Inline: True
```
```
In kernel/auditsc.c (ffffffff8116fd02)
Location: include/linux/sched.h:1369
Inline: True
```
```
In kernel/taskstats.c (ffffffff81189955)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81189d9b)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (ffffffff81360ece)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff8136467f)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81364841)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff81427153)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff81477af9)
Location: include/linux/sched.h:1369
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff810b1e2c)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff81158570)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff81176180)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/auditsc.c (ffffffff8117bb82)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/taskstats.c (ffffffff81195898)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81195cab)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (ffffffff8137912e)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff8137c90f)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff8137cad1)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff81440e93)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff81491899)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff810ba436)
Location: include/linux/sched.h:1404
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff8116960b)
Location: include/linux/sched.h:1404
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff8118897f)
Location: include/linux/sched.h:1404
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118ea85)
Location: include/linux/sched.h:1404
Inline: True
```
```
In kernel/taskstats.c (ffffffff811aac1c)
Location: include/linux/sched.h:1404
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811aae86)
Location: include/linux/sched.h:1404
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff81214d78)
Location: include/linux/sched.h:1404
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/proc/array.c (ffffffff813c21da)
Location: include/linux/sched.h:1404
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff813c629f)
Location: include/linux/sched.h:1404
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813c6467)
Location: include/linux/sched.h:1404
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff81491c4a)
Location: include/linux/sched.h:1404
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff814e8cc2)
Location: include/linux/sched.h:1404
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff810b56c6)
Location: include/linux/sched.h:1463
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff81165cfb)
Location: include/linux/sched.h:1463
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff81185cc3)
Location: include/linux/sched.h:1463
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118bc68)
Location: include/linux/sched.h:1463
Inline: True
```
```
In kernel/taskstats.c (ffffffff811a81cc)
Location: include/linux/sched.h:1463
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811a8436)
Location: include/linux/sched.h:1463
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff81216918)
Location: include/linux/sched.h:1463
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/proc/array.c (ffffffff813d4329)
Location: include/linux/sched.h:1463
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff813d8241)
Location: include/linux/sched.h:1463
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813d841c)
Location: include/linux/sched.h:1463
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff814af97c)
Location: include/linux/sched.h:1463
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff81506002)
Location: include/linux/sched.h:1463
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff810b72be)
Location: include/linux/sched.h:1485
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff81166a2b)
Location: include/linux/sched.h:1485
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff81186cb3)
Location: include/linux/sched.h:1485
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118cb1d)
Location: include/linux/sched.h:1485
Inline: True
```
```
In kernel/taskstats.c (ffffffff811a8c2d)
Location: include/linux/sched.h:1485
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811a8fb6)
Location: include/linux/sched.h:1485
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff81219652)
Location: include/linux/sched.h:1485
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/proc/array.c (ffffffff813db169)
Location: include/linux/sched.h:1485
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff813df0ef)
Location: include/linux/sched.h:1485
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813df2b7)
Location: include/linux/sched.h:1485
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff814b57bc)
Location: include/linux/sched.h:1485
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff8150cb46)
Location: include/linux/sched.h:1485
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff810c8975)
Location: include/linux/sched.h:1583
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff8118c1eb)
Location: include/linux/sched.h:1583
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff811af0e3)
Location: include/linux/sched.h:1583
Inline: True
```
```
In kernel/auditsc.c (ffffffff811b573a)
Location: include/linux/sched.h:1583
Inline: True
```
```
In kernel/taskstats.c (ffffffff811d2779)
Location: include/linux/sched.h:1583
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811d2b0b)
Location: include/linux/sched.h:1583
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff8124fd12)
Location: include/linux/sched.h:1583
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/proc/array.c (ffffffff8142c7ed)
Location: include/linux/sched.h:1583
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff81430a9f)
Location: include/linux/sched.h:1583
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81430c67)
Location: include/linux/sched.h:1583
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff8150deac)
Location: include/linux/sched.h:1583
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff8156a676)
Location: include/linux/sched.h:1583
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff810e0ded)
Location: include/linux/sched.h:1595
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/acct.c (ffffffff811bb5df)
Location: include/linux/sched.h:1595
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff811e13b1)
Location: include/linux/sched.h:1595
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_task_info
```
```
In kernel/auditsc.c (ffffffff811e891d)
Location: include/linux/sched.h:1595
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_uring
```
```
In kernel/taskstats.c (ffffffff8120701c)
Location: include/linux/sched.h:1595
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8120745f)
Location: include/linux/sched.h:1595
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff812971a3)
Location: include/linux/sched.h:1595
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/proc/array.c (ffffffff814a60c1)
Location: include/linux/sched.h:1595
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff814aa7df)
Location: include/linux/sched.h:1595
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff814aa9b7)
Location: include/linux/sched.h:1595
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff815a097c)
Location: include/linux/sched.h:1595
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff81606631)
Location: include/linux/sched.h:1595
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff81100fd2)
Location: include/linux/sched.h:1617
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/acct.c (ffffffff811fd3ff)
Location: include/linux/sched.h:1617
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff81227231)
Location: include/linux/sched.h:1617
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_task_info
```
```
In kernel/auditsc.c (ffffffff8122e98d)
Location: include/linux/sched.h:1617
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_uring
```
```
In kernel/taskstats.c (ffffffff8124f38c)
Location: include/linux/sched.h:1617
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8124f7ef)
Location: include/linux/sched.h:1617
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff812f1fb3)
Location: include/linux/sched.h:1617
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/proc/array.c (ffffffff8153b701)
Location: include/linux/sched.h:1617
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff8154043f)
Location: include/linux/sched.h:1617
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81540647)
Location: include/linux/sched.h:1617
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff8164a30c)
Location: include/linux/sched.h:1617
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff816b7aa1)
Location: include/linux/sched.h:1617
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff8110d01a)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/acct.c (ffffffff81212586)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff8123d851)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_task_info
```
```
In kernel/auditsc.c (ffffffff8124486d)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_uring
```
```
In kernel/taskstats.c (ffffffff8126673c)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81266b9f)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff8131eb39)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/proc/array.c (ffffffff81573a2c)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff815787ff)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81578a07)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff81682853)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff816f0471)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff811169fa)
Location: include/linux/pid.h:285
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/acct.c (ffffffff81229c06)
Location: include/linux/pid.h:285
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff81257772)
Location: include/linux/pid.h:285
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_task_info
```
```
In kernel/auditsc.c (ffffffff8125e6cd)
Location: include/linux/pid.h:285
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_uring
```
```
In kernel/taskstats.c (ffffffff8128062c)
Location: include/linux/pid.h:285
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81280ac2)
Location: include/linux/pid.h:285
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff81340f69)
Location: include/linux/pid.h:285
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/proc/array.c (ffffffff815ac332)
Location: include/linux/pid.h:285
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff815b0f2f)
Location: include/linux/pid.h:285
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff815b1187)
Location: include/linux/pid.h:285
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff816bec53)
Location: include/linux/pid.h:285
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff8172d241)
Location: include/linux/pid.h:285
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffff80001010da80)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffff8000101c7e30)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffff8000101eb134)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/auditsc.c (ffff8000101eff50)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/taskstats.c (ffff80001020db4c)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffff80001020df74)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (ffff8000104455ec)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffff800010449270)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffff80001044942c)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffff80001052996c)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffff800010585f54)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (c0365e8c)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (c040ec24)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (c042ad28)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/auditsc.c (c043115c)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/taskstats.c (c044c540)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (c044ca4c)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (c060a628)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (c060e314)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (c060e520)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (c06e3bdc)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/tomoyo/realpath.c (c07378a4)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (c000000000154e38)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (c000000000230008)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (c00000000025c6ec)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/auditsc.c (c000000000263198)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/taskstats.c (c00000000028bbe0)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (c00000000028c168)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (c00000000055afec)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (c00000000055fcfc)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (c00000000055ff8c)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (c000000000675450)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (c0000000006f5b5c)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffe0000cec04)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffe000147b92)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffe00015f9a6)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/auditsc.c (ffffffe000163b76)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/taskstats.c (ffffffe00016ea58)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffe00016ee14)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (ffffffe0002db544)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffe0002dec1c)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffe0002dedb6)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffe00038c842)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffe0003d5908)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff810ac19c)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff81150b90)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff8116e7a0)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/auditsc.c (ffffffff811741a2)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/taskstats.c (ffffffff8118deb8)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8118e2cb)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (ffffffff8137170e)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff81374eef)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813750b1)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff81439473)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff81489e79)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff8109ab2c)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff81143e3a)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff81161940)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/auditsc.c (ffffffff81167342)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/taskstats.c (ffffffff81180fc8)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811813ee)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (ffffffff813621e9)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff813659bf)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81365b81)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff81429ee3)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff8147a899)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff810ab6fc)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff8114ea40)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff8116c570)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/auditsc.c (ffffffff81171f72)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/taskstats.c (ffffffff8118bc88)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8118c09b)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (ffffffff8136f1de)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff813729bf)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81372b81)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff81435613)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff81485f19)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
In kernel/signal.c (ffffffff810b37f5)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/acct.c (ffffffff8115b817)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/audit.c (ffffffff81179d20)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/auditsc.c (ffffffff81180135)
Location: include/linux/sched.h:1363
Inline: True
```
```
In kernel/taskstats.c (ffffffff81199605)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81199a20)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/proc/array.c (ffffffff81382b6e)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/self.c (ffffffff8138639f)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81386561)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In ipc/mqueue.c (ffffffff8144ccbd)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In security/tomoyo/realpath.c (ffffffff8149da59)
Location: include/linux/sched.h:1363
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
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
</ul>
