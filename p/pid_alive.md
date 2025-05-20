# Function: <code>pid_alive</code>

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
In kernel/pid.c (0)
Location: include/linux/sched.h:2002
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:2002
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/sched.h:2002
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:2002
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/sched.h:2002
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/sched.h:2002
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:2002
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/sched.h:2002
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
In kernel/pid.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/sched.h:2141
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
In kernel/pid.c (0)
Location: include/linux/sched.h:2228
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:2228
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/sched.h:2228
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:2228
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/sched.h:2228
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/sched.h:2228
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:2228
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/sched.h:2228
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
In kernel/pid.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/sched.h:1177
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
In kernel/pid.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:1177
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/sched.h:1177
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
In kernel/pid.c (ffffffff810b081a)
Location: include/linux/sched.h:1269
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
```
```
In kernel/sched/core.c (ffffffff810c2e7c)
Location: include/linux/sched.h:1269
Inline: True
```
```
In kernel/audit.c (ffffffff811512e1)
Location: include/linux/sched.h:1269
Inline: True
```
```
In kernel/auditsc.c (ffffffff81155d01)
Location: include/linux/sched.h:1269
Inline: True
```
```
In kernel/hung_task.c (ffffffff81169c8f)
Location: include/linux/sched.h:1269
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/tsacct.c (ffffffff8116f3c5)
Location: include/linux/sched.h:1269
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff811d313b)
Location: include/linux/sched.h:1269
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_pid_type
```
```
In fs/proc/base.c (ffffffff8131f776)
Location: include/linux/sched.h:1269
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813222e0)
Location: include/linux/sched.h:1269
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
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
In kernel/pid.c (ffffffff810b995e)
Location: include/linux/sched.h:1271
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
```
```
In kernel/sched/core.c (ffffffff810cc12e)
Location: include/linux/sched.h:1271
Inline: True
```
```
In kernel/audit.c (ffffffff8115df8c)
Location: include/linux/sched.h:1271
Inline: True
```
```
In kernel/auditsc.c (ffffffff81163098)
Location: include/linux/sched.h:1271
Inline: True
```
```
In kernel/hung_task.c (ffffffff81176b5b)
Location: include/linux/sched.h:1271
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/tsacct.c (ffffffff8117cec5)
Location: include/linux/sched.h:1271
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff811e342b)
Location: include/linux/sched.h:1271
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_pid_type
```
```
In fs/proc/base.c (ffffffff813368a6)
Location: include/linux/sched.h:1271
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813393f0)
Location: include/linux/sched.h:1271
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/yama/yama_lsm.c (ffffffff8146c093)
Location: include/linux/sched.h:1271
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816989e4)
Location: include/linux/sched.h:1271
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/pid.c (ffffffff810bf75e)
Location: include/linux/sched.h:1343
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
```
```
In kernel/sched/core.c (ffffffff810d44fa)
Location: include/linux/sched.h:1343
Inline: True
```
```
In kernel/audit.c (ffffffff8116a2ba)
Location: include/linux/sched.h:1343
Inline: True
```
```
In kernel/auditsc.c (ffffffff8116fceb)
Location: include/linux/sched.h:1343
Inline: True
```
```
In kernel/hung_task.c (ffffffff8118395f)
Location: include/linux/sched.h:1343
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/tsacct.c (ffffffff81189d86)
Location: include/linux/sched.h:1343
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff811fa5fb)
Location: include/linux/sched.h:1343
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_pid_type
```
```
In fs/proc/base.c (ffffffff8135e8ef)
Location: include/linux/sched.h:1343
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813603df)
Location: include/linux/sched.h:1343
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff81499097)
Location: include/linux/sched.h:1343
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816d150c)
Location: include/linux/sched.h:1343
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/pid.c (ffffffff810c5b2e)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
```
```
In kernel/sched/core.c (ffffffff810deb0c)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/audit.c (ffffffff8117615a)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/auditsc.c (ffffffff8117bb6b)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/hung_task.c (ffffffff8118f7cf)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/tsacct.c (ffffffff81195c96)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff812076cb)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_pid_type
```
```
In fs/proc/base.c (ffffffff81376b4f)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8137863f)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff814b2fc7)
Location: include/linux/sched.h:1337
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816f532c)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/sched/core.c (ffffffff810e6d7d)
Location: include/linux/sched.h:1378
Inline: True
```
```
In kernel/audit.c (ffffffff81188959)
Location: include/linux/sched.h:1378
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118ea6e)
Location: include/linux/sched.h:1378
Inline: True
```
```
In kernel/hung_task.c (ffffffff811a430a)
Location: include/linux/sched.h:1378
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/tsacct.c (ffffffff811aae71)
Location: include/linux/sched.h:1378
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff81237d47)
Location: include/linux/sched.h:1378
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
```
In fs/proc/base.c (ffffffff813bf8b3)
Location: include/linux/sched.h:1378
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813c1720)
Location: include/linux/sched.h:1378
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff8151245f)
Location: include/linux/sched.h:1378
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff817adc0a)
Location: include/linux/sched.h:1378
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/sched/core.c (ffffffff81bdc598)
Location: include/linux/sched.h:1437
Inline: True
```
```
In kernel/audit.c (ffffffff81185caf)
Location: include/linux/sched.h:1437
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118bc50)
Location: include/linux/sched.h:1437
Inline: True
```
```
In kernel/hung_task.c (ffffffff811a145f)
Location: include/linux/sched.h:1437
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/tsacct.c (ffffffff811a8421)
Location: include/linux/sched.h:1437
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff81241b17)
Location: include/linux/sched.h:1437
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
```
In fs/proc/base.c (ffffffff813d173d)
Location: include/linux/sched.h:1437
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813d3610)
Location: include/linux/sched.h:1437
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff8152f304)
Location: include/linux/sched.h:1437
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff817c27aa)
Location: include/linux/sched.h:1437
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/sched/core.c (ffffffff81bce738)
Location: include/linux/sched.h:1459
Inline: True
```
```
In kernel/audit.c (ffffffff81186ca0)
Location: include/linux/sched.h:1459
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118cb04)
Location: include/linux/sched.h:1459
Inline: True
```
```
In kernel/hung_task.c (ffffffff811a20b7)
Location: include/linux/sched.h:1459
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/tsacct.c (ffffffff811a8fa1)
Location: include/linux/sched.h:1459
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff812455c7)
Location: include/linux/sched.h:1459
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
```
In fs/proc/base.c (ffffffff813d8633)
Location: include/linux/sched.h:1459
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813da440)
Location: include/linux/sched.h:1459
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff8153524d)
Location: include/linux/sched.h:1459
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff817a5c6a)
Location: include/linux/sched.h:1459
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/sched/core.c (ffffffff810eec78)
Location: include/linux/sched.h:1557
Inline: True
```
```
In kernel/audit.c (ffffffff811af0d0)
Location: include/linux/sched.h:1557
Inline: True
```
```
In kernel/auditsc.c (ffffffff811b5722)
Location: include/linux/sched.h:1557
Inline: True
```
```
In kernel/hung_task.c (ffffffff811cb86c)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/tsacct.c (ffffffff811d2af6)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff81280577)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
```
In fs/proc/base.c (ffffffff81429d63)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8142bb70)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff81593769)
Location: include/linux/sched.h:1557
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff818315ea)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/sched/core.c (ffffffff8110bb03)
Location: include/linux/sched.h:1569
Inline: True
```
```
In kernel/audit.c (ffffffff811e139c)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_task_info
```
```
In kernel/auditsc.c (ffffffff811e890a)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_uring
```
```
In kernel/hung_task.c (ffffffff811ff633)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/tsacct.c (ffffffff81207495)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff812d533a)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
```
In fs/proc/base.c (ffffffff814a31ef)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff814a57df)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff81635aa0)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
```
In drivers/connector/cn_proc.c (ffffffff81972b70)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/sched/core.c (ffffffff81131ec9)
Location: include/linux/sched.h:1591
Inline: True
```
```
In kernel/audit.c (ffffffff8122721c)
Location: include/linux/sched.h:1591
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_task_info
```
```
In kernel/auditsc.c (ffffffff8122e97a)
Location: include/linux/sched.h:1591
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_uring
```
```
In kernel/hung_task.c (ffffffff81247048)
Location: include/linux/sched.h:1591
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/tsacct.c (ffffffff8124f825)
Location: include/linux/sched.h:1591
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/task_iter.c (ffffffff812f7050)
Location: include/linux/sched.h:1591
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_group_seq_get_next
```
```
In kernel/events/core.c (ffffffff8133df3a)
Location: include/linux/sched.h:1591
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
```
In fs/proc/base.c (ffffffff8153846f)
Location: include/linux/sched.h:1591
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8153adef)
Location: include/linux/sched.h:1591
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff816ec7b0)
Location: include/linux/sched.h:1591
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
```
In drivers/connector/cn_proc.c (ffffffff81addea0)
Location: include/linux/sched.h:1591
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/sched/core.c (ffffffff81140141)
Location: include/linux/sched.h:1600
Inline: True
```
```
In kernel/audit.c (ffffffff8123d83c)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_task_info
```
```
In kernel/auditsc.c (ffffffff8124485a)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_uring
```
```
In kernel/hung_task.c (ffffffff8125e0d8)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/tsacct.c (ffffffff81266bd5)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/task_iter.c (ffffffff81324f10)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_group_seq_get_next
```
```
In kernel/events/core.c (ffffffff8136f11a)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
```
In fs/proc/base.c (ffffffff815706b2)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff815730fc)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff81726be0)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
```
In drivers/connector/cn_proc.c (ffffffff81b2c110)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/sched/core.c (ffffffff8114b0a3)
Location: include/linux/pid.h:259
Inline: True
```
```
In kernel/audit.c (ffffffff8125775d)
Location: include/linux/pid.h:259
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_task_info
```
```
In kernel/auditsc.c (ffffffff8125e6ba)
Location: include/linux/pid.h:259
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_uring
```
```
In kernel/hung_task.c (ffffffff81278018)
Location: include/linux/pid.h:259
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/tsacct.c (ffffffff81280af8)
Location: include/linux/pid.h:259
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff813983ba)
Location: include/linux/pid.h:259
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
```
In fs/proc/base.c (ffffffff815a915d)
Location: include/linux/pid.h:259
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff815ab8bc)
Location: include/linux/pid.h:259
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff81767e30)
Location: include/linux/pid.h:259
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
```
In drivers/connector/cn_proc.c (ffffffff81b83870)
Location: include/linux/pid.h:259
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/pid.c (ffff800010124048)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
```
```
In kernel/sched/core.c (ffff80001013e570)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/audit.c (ffff8000101eb124)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/auditsc.c (ffff8000101eff40)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/hung_task.c (ffff800010206e98)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/tsacct.c (ffff80001020df64)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffff8000102910fc)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_pid_type
```
```
In fs/proc/base.c (ffff800010442200)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffff800010444cd8)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffff8000105aa874)
Location: include/linux/sched.h:1337
Inline: True
```
```
In drivers/connector/cn_proc.c (ffff8000108de918)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/pid.c (c037738c)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
```
```
In kernel/sched/core.c (c038e54c)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/audit.c (c042ad18)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/auditsc.c (c0431148)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/hung_task.c (c0445c70)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/tsacct.c (c044ca3c)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (c04c1138)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_pid_type
```
```
In fs/proc/base.c (c0607a64)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (c06098c4)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (c075a7c4)
Location: include/linux/sched.h:1337
Inline: True
```
```
In drivers/connector/cn_proc.c (c09cda14)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/pid.c (c00000000016dd90)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
```
```
In kernel/sched/core.c (c00000000017e540)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/audit.c (c00000000025c6d4)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/auditsc.c (c000000000263180)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/hung_task.c (c000000000283410)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/tsacct.c (c00000000028c158)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (c00000000033ee64)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_pid_type
```
```
In fs/proc/base.c (c000000000557790)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (c00000000055a0d0)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (c0000000007286f0)
Location: include/linux/sched.h:1337
Inline: True
```
```
In drivers/connector/cn_proc.c (c0000000009722a4)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/pid.c (ffffffe0000dc38e)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
```
```
In kernel/sched/core.c (ffffffe0000e6264)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/audit.c (ffffffe00015f99a)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/auditsc.c (ffffffe000163b6a)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/hung_task.c (ffffffe0001696c8)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/tsacct.c (ffffffe00016ee08)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffe0001c3cd0)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_pid_type
```
```
In fs/proc/base.c (ffffffe0002d8ed8)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffe0002dac9c)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffe0003f376c)
Location: include/linux/sched.h:1337
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffe000574bec)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/pid.c (ffffffff810bfeae)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
```
```
In kernel/sched/core.c (ffffffff810d8cfc)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/audit.c (ffffffff8116e77a)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/auditsc.c (ffffffff8117418b)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/hung_task.c (ffffffff81187def)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/tsacct.c (ffffffff8118e2b6)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff811ffceb)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_pid_type
```
```
In fs/proc/base.c (ffffffff8136f12f)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff81370c1f)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff814ab5a7)
Location: include/linux/sched.h:1337
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816bab1c)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/pid.c (ffffffff810ae6be)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
```
```
In kernel/sched/core.c (ffffffff810c7707)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/audit.c (ffffffff8116191a)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/auditsc.c (ffffffff8116732b)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/hung_task.c (ffffffff8117af2f)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/tsacct.c (ffffffff811813d9)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff811f2a3b)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_pid_type
```
```
In fs/proc/base.c (ffffffff8135fbbf)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813616af)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff8149bfc7)
Location: include/linux/sched.h:1337
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff8169875c)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/pid.c (ffffffff810bf3fe)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
```
```
In kernel/sched/core.c (ffffffff810d503c)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/audit.c (ffffffff8116c54a)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/auditsc.c (ffffffff81171f5b)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/hung_task.c (ffffffff81185bbf)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/tsacct.c (ffffffff8118c086)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff811fdabb)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_pid_type
```
```
In fs/proc/base.c (ffffffff8136cbff)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8136e6ef)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff814a7647)
Location: include/linux/sched.h:1337
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816e8fec)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
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
In kernel/pid.c (ffffffff810c7871)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
```
```
In kernel/sched/core.c (ffffffff810e08e1)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/audit.c (ffffffff81179d0d)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118011e)
Location: include/linux/sched.h:1337
Inline: True
```
```
In kernel/hung_task.c (ffffffff81193509)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/tsacct.c (ffffffff81199a0b)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/events/core.c (ffffffff8120cb1b)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_pid_type
```
```
In fs/proc/base.c (ffffffff81380504)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff81382047)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/yama/yama_lsm.c (ffffffff814bff8a)
Location: include/linux/sched.h:1337
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81703811)
Location: include/linux/sched.h:1337
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
```
</details>
</li>
</ul>

## Differences
