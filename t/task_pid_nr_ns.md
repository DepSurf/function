# Function: <code>task_pid_nr_ns</code>

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
In kernel/signal.c (ffffffff8108e884)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - kernel/signal.c:send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/taskstats.c (ffffffff8113ecd3)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8113f124)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff81178b1e)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_mmap_output
```
```
In fs/exec.c (ffffffff8121433b)
Location: include/linux/sched.h:1920
Inline: True
```
```
In fs/proc/base.c (ffffffff8127e59f)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff81280e15)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/thread_self.c (ffffffff81283d3a)
Location: include/linux/sched.h:1920
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_readlink
  - fs/proc/thread_self.c:proc_thread_self_follow_link
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
In kernel/signal.c (ffffffff8109198a)
Location: include/linux/sched.h:2059
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
```
```
In kernel/taskstats.c (ffffffff81147306)
Location: include/linux/sched.h:2059
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8114772a)
Location: include/linux/sched.h:2059
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff811894d0)
Location: include/linux/sched.h:2059
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
```
```
In fs/exec.c (ffffffff8123b0cd)
Location: include/linux/sched.h:2059
Inline: True
```
```
In fs/proc/base.c (ffffffff812ab5b3)
Location: include/linux/sched.h:2059
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff812adebf)
Location: include/linux/sched.h:2059
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/thread_self.c (ffffffff812b0e57)
Location: include/linux/sched.h:2059
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_readlink
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
In kernel/signal.c (ffffffff8109691a)
Location: include/linux/sched.h:2146
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
```
```
In kernel/taskstats.c (ffffffff811511a6)
Location: include/linux/sched.h:2146
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811515ca)
Location: include/linux/sched.h:2146
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff811988a0)
Location: include/linux/sched.h:2146
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
```
```
In fs/exec.c (ffffffff8124dea9)
Location: include/linux/sched.h:2146
Inline: True
```
```
In fs/proc/base.c (ffffffff812c0c93)
Location: include/linux/sched.h:2146
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff812c3842)
Location: include/linux/sched.h:2146
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/thread_self.c (ffffffff812c66f7)
Location: include/linux/sched.h:2146
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff81093c31)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
```
```
In kernel/taskstats.c (ffffffff8115381b)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81153c4d)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff811a067c)
Location: include/linux/sched.h:1151
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
In fs/exec.c (ffffffff81259efb)
Location: include/linux/sched.h:1151
Inline: True
```
```
In fs/proc/base.c (ffffffff812ce078)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff812d0acf)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/thread_self.c (ffffffff812d38fc)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff8109ab21)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
```
```
In kernel/sched/debug.c (ffffffff810d92ef)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff8116001b)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8116044d)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff8127c19b)
Location: include/linux/sched.h:1151
Inline: True
```
```
In fs/proc/base.c (ffffffff812f28ce)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff812f5306)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/thread_self.c (ffffffff812f812c)
Location: include/linux/sched.h:1151
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff8109ea54)
Location: include/linux/sched.h:1243
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
```
```
In kernel/sched/debug.c (ffffffff810e02eb)
Location: include/linux/sched.h:1243
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff8116ef57)
Location: include/linux/sched.h:1243
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8116f394)
Location: include/linux/sched.h:1243
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812a2e31)
Location: include/linux/sched.h:1243
Inline: True
```
```
In fs/proc/base.c (ffffffff8131f72b)
Location: include/linux/sched.h:1243
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff81322685)
Location: include/linux/sched.h:1243
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/thread_self.c (ffffffff81325467)
Location: include/linux/sched.h:1243
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff810a6d58)
Location: include/linux/sched.h:1245
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
```
```
In kernel/sched/debug.c (ffffffff810eaa6b)
Location: include/linux/sched.h:1245
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff8117ca57)
Location: include/linux/sched.h:1245
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8117ce94)
Location: include/linux/sched.h:1245
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812b7dc9)
Location: include/linux/sched.h:1245
Inline: True
```
```
In fs/proc/base.c (ffffffff8133685b)
Location: include/linux/sched.h:1245
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8133979a)
Location: include/linux/sched.h:1245
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/thread_self.c (ffffffff8133c607)
Location: include/linux/sched.h:1245
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff810ace1a)
Location: include/linux/sched.h:1317
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (ffffffff810f186b)
Location: include/linux/sched.h:1317
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff81189908)
Location: include/linux/sched.h:1317
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81189d55)
Location: include/linux/sched.h:1317
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812d42cd)
Location: include/linux/sched.h:1317
Inline: True
```
```
In fs/proc/base.c (ffffffff8135e947)
Location: include/linux/sched.h:1317
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff81360778)
Location: include/linux/sched.h:1317
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff81364857)
Location: include/linux/sched.h:1317
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff810b343a)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (ffffffff810fd52b)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff8119584b)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81195c65)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812e5e5d)
Location: include/linux/sched.h:1311
Inline: True
```
```
In fs/proc/base.c (ffffffff81376ba7)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813789d8)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff8137cae7)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff810bbe62)
Location: include/linux/sched.h:1352
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (ffffffff81107ccb)
Location: include/linux/sched.h:1352
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff811aabcf)
Location: include/linux/sched.h:1352
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811aae40)
Location: include/linux/sched.h:1352
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff81214d59)
Location: include/linux/sched.h:1352
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/exec.c (ffffffff8131cc0b)
Location: include/linux/sched.h:1352
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/proc/base.c (ffffffff813bf865)
Location: include/linux/sched.h:1352
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813c1ab9)
Location: include/linux/sched.h:1352
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff813c647a)
Location: include/linux/sched.h:1352
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff810b7132)
Location: include/linux/sched.h:1411
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (ffffffff811064db)
Location: include/linux/sched.h:1411
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff811a817f)
Location: include/linux/sched.h:1411
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811a83f0)
Location: include/linux/sched.h:1411
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff812168f9)
Location: include/linux/sched.h:1411
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/exec.c (ffffffff81327d97)
Location: include/linux/sched.h:1411
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/proc/base.c (ffffffff813d16ef)
Location: include/linux/sched.h:1411
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813d39b4)
Location: include/linux/sched.h:1411
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff813d842f)
Location: include/linux/sched.h:1411
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff810b8732)
Location: include/linux/sched.h:1433
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (ffffffff8110851b)
Location: include/linux/sched.h:1433
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff811a8bd2)
Location: include/linux/sched.h:1433
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811a8f70)
Location: include/linux/sched.h:1433
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff81219636)
Location: include/linux/sched.h:1433
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/exec.c (ffffffff8132dcc7)
Location: include/linux/sched.h:1433
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/proc/base.c (ffffffff813d85e5)
Location: include/linux/sched.h:1433
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813da7e4)
Location: include/linux/sched.h:1433
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff813df2ca)
Location: include/linux/sched.h:1433
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff810cac22)
Location: include/linux/sched.h:1531
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (ffffffff8112668b)
Location: include/linux/sched.h:1531
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff811d271e)
Location: include/linux/sched.h:1531
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811d2ac5)
Location: include/linux/sched.h:1531
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff8124fcf6)
Location: include/linux/sched.h:1531
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/exec.c (ffffffff8137b4a7)
Location: include/linux/sched.h:1531
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/proc/base.c (ffffffff81429d15)
Location: include/linux/sched.h:1531
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8142bf1e)
Location: include/linux/sched.h:1531
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff81430c7a)
Location: include/linux/sched.h:1531
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff810e40a5)
Location: include/linux/sched.h:1543
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/build_utility.c (ffffffff81146dcb)
Location: include/linux/sched.h:1543
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff81206fbe)
Location: include/linux/sched.h:1543
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81207449)
Location: include/linux/sched.h:1543
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff81297184)
Location: include/linux/sched.h:1543
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/exec.c (ffffffff813fa564)
Location: include/linux/sched.h:1543
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/proc/base.c (ffffffff814a31a1)
Location: include/linux/sched.h:1543
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff814a5b59)
Location: include/linux/sched.h:1543
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff814aa9ca)
Location: include/linux/sched.h:1543
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff81104725)
Location: include/linux/sched.h:1565
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/build_utility.c (ffffffff8117480b)
Location: include/linux/sched.h:1565
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff8124f32e)
Location: include/linux/sched.h:1565
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8124f7d9)
Location: include/linux/sched.h:1565
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff812f1f94)
Location: include/linux/sched.h:1565
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/exec.c (ffffffff81484094)
Location: include/linux/sched.h:1565
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/proc/base.c (ffffffff81538421)
Location: include/linux/sched.h:1565
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8153b169)
Location: include/linux/sched.h:1565
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff8154065a)
Location: include/linux/sched.h:1565
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff811109a5)
Location: include/linux/sched.h:1574
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/build_utility.c (ffffffff81185414)
Location: include/linux/sched.h:1574
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff812666de)
Location: include/linux/sched.h:1574
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81266b89)
Location: include/linux/sched.h:1574
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/helpers.c (ffffffff8131eb1a)
Location: include/linux/sched.h:1574
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/exec.c (ffffffff814b89a4)
Location: include/linux/sched.h:1574
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/proc/base.c (ffffffff81570664)
Location: include/linux/sched.h:1574
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff81573476)
Location: include/linux/sched.h:1574
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff81578a1a)
Location: include/linux/sched.h:1574
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff8111a305)
Location: include/linux/pid.h:233
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/build_utility.c (ffffffff81193b74)
Location: include/linux/pid.h:233
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff812805ce)
Location: include/linux/pid.h:233
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81280aac)
Location: include/linux/pid.h:233
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/bpf_trace.c (ffffffff812e53e2)
Location: include/linux/pid.h:233
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_fill_link_info
```
```
In kernel/bpf/helpers.c (ffffffff81340f4a)
Location: include/linux/pid.h:233
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
```
In fs/exec.c (ffffffff814eaeb4)
Location: include/linux/pid.h:233
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/proc/base.c (ffffffff815a910d)
Location: include/linux/pid.h:233
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff815abc39)
Location: include/linux/pid.h:233
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff815b119a)
Location: include/linux/pid.h:233
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffff80001010f274)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (ffff800010162dd4)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffff80001020db00)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffff80001020df38)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffff80001038e1a4)
Location: include/linux/sched.h:1311
Inline: True
```
```
In fs/proc/base.c (ffff8000104421b0)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffff800010445078)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffff80001044943c)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (c0366fb0)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (c03af3f0)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (c044c4ec)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (c044ca0c)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (c0575c00)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/proc/base.c (c0607a14)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (c0609ce4)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (c060e54c)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (c000000000156768)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (c0000000001b9544)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (c00000000028bb8c)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (c00000000028c118)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (c0000000004864a4)
Location: include/linux/sched.h:1311
Inline: True
```
```
In fs/proc/base.c (c000000000557734)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (c00000000055a5a0)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (c00000000055ffa0)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffe0000cf802)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:send_signal
```
```
In kernel/sched/debug.c (ffffffe000106994)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffe00016ea08)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffe00016edc2)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffe00025ecb0)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/proc/base.c (ffffffe0002d8e9a)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffe0002db088)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffe0002dedc8)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff810ad7aa)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (ffffffff810f684b)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff8118de6b)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8118e285)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812de43d)
Location: include/linux/sched.h:1311
Inline: True
```
```
In fs/proc/base.c (ffffffff8136f187)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff81370fb8)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff813750c7)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff8109c12a)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (ffffffff810e6a1b)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff81180f7b)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811813a8)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812cf76d)
Location: include/linux/sched.h:1311
Inline: True
```
```
In fs/proc/base.c (ffffffff8135fc17)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff81361a48)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff81365b97)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff810acd0a)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (ffffffff810f3a5b)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff8118bc3b)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff8118c055)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812dc24d)
Location: include/linux/sched.h:1311
Inline: True
```
```
In fs/proc/base.c (ffffffff8136cc57)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8136ea88)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff81372b97)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
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
In kernel/signal.c (ffffffff810b4ebf)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/debug.c (ffffffff810fea4b)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/taskstats.c (ffffffff811995b8)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff811999d5)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812ecfdc)
Location: include/linux/sched.h:1311
Inline: True
```
```
In fs/proc/base.c (ffffffff81380565)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813823e8)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
```
```
In fs/proc/thread_self.c (ffffffff81386577)
Location: include/linux/sched.h:1311
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
</details>
</li>
</ul>

## Differences
