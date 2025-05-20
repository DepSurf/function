# Function: <code>task_dfl_cgroup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810bc314)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810c2ef5)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810cbe3a)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cf5f2)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810d520b)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/bpf/cgroup.c (ffffffff811b22b9)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffff810c39e8)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810c93c2)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810d3543)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d7144)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810dd1db)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/bpf/helpers.c (ffffffff811c0b0f)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff811d1849)
Location: include/linux/cgroup.h:525
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffff810ccca8)
Location: include/linux/cgroup.h:527
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810d37b2)
Location: include/linux/cgroup.h:527
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810dc8e2)
Location: include/linux/cgroup.h:527
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e1690)
Location: include/linux/cgroup.h:527
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e6e3b)
Location: include/linux/cgroup.h:527
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/bpf/helpers.c (ffffffff811d1faf)
Location: include/linux/cgroup.h:527
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff811e140b)
Location: include/linux/cgroup.h:527
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffff810d5089)
Location: include/linux/cgroup.h:540
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810daca5)
Location: include/linux/cgroup.h:540
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e3883)
Location: include/linux/cgroup.h:540
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e8148)
Location: include/linux/cgroup.h:540
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810edacf)
Location: include/linux/cgroup.h:540
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff8115abe3)
Location: include/linux/cgroup.h:540
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (ffffffff8115e307)
Location: include/linux/cgroup.h:540
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff811e62cf)
Location: include/linux/cgroup.h:540
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff811f8708)
Location: include/linux/cgroup.h:540
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffff810df648)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810e4bc5)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810ef2b9)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f3517)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f96ae)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff81166893)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (ffffffff81169ef7)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff811f2a1f)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff81205578)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffff810e7998)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ee1d5)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f8cb2)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fcc02)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff811037be)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff81177a56)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (ffffffff8117ba73)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff8121487f)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff8122e653)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffff810e5688)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ebfe3)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f6ec5)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fb112)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff81101ede)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff811747cb)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (ffffffff811788c3)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff8121635f)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff81236bc3)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffff810e7648)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ee97f)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f9015)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fd31a)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff8110424e)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff8117538f)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (ffffffff81179433)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff8121906f)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff8123aeb2)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffff810fecdf)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff81106fc6)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff8111450d)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff811196ea)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff81121350)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff8119c8e1)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
```
```
In kernel/cgroup/freezer.c (ffffffff811a0d43)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff8124fc14)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff81275a49)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/fair.c (ffffffff81124157)
Location: include/linux/cgroup.h:549
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81136180)
Location: include/linux/cgroup.h:549
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff811440c4)
Location: include/linux/cgroup.h:549
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff811ccba1)
Location: include/linux/cgroup.h:549
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
```
```
In kernel/cgroup/freezer.c (ffffffff811d1543)
Location: include/linux/cgroup.h:549
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff8129704f)
Location: include/linux/cgroup.h:549
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff812c54bc)
Location: include/linux/cgroup.h:549
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/fair.c (ffffffff8114c0f8)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81160760)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:__account_forceidle_time
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8117ab38)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff81210131)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
```
```
In kernel/cgroup/freezer.c (ffffffff81215103)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff812f1e4b)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff8132aa02)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
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
In kernel/sched/fair.c (ffffffff8115a388)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81170e86)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:__account_forceidle_time
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8118b698)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff81225b2c)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
```
```
In kernel/cgroup/freezer.c (ffffffff8122aa33)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff8131e9cb)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff8135ab42)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
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
In kernel/sched/fair.c (ffffffff81164b6a)
Location: include/linux/cgroup.h:488
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr_common
```
```
In kernel/sched/build_policy.c (ffffffff8118205e)
Location: include/linux/cgroup.h:488
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__account_forceidle_time
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
```
In kernel/sched/build_utility.c (ffffffff81199fc8)
Location: include/linux/cgroup.h:488
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff8123d7bf)
Location: include/linux/cgroup.h:488
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
```
```
In kernel/cgroup/freezer.c (ffffffff812429f3)
Location: include/linux/cgroup.h:488
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff81340dfb)
Location: include/linux/cgroup.h:488
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff81383732)
Location: include/linux/cgroup.h:488
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
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
In kernel/sched/cputime.c (ffff80001013ef80)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffff800010144908)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffff8000101504e0)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffff800010155728)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffff80001015e060)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8614)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (ffff8000101dd834)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffff800010276394)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffff80001028e134)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (c038ef54)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (c0392228)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c039e168)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c03a30a0)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c03a9f0c)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (c041b274)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (c041f3d8)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (c04a89d8)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (c04be0c8)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (c00000000018e12c)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (c000000000195b4c)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c0000000001a44ac)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c0000000001a9940)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c0000000001b2ca0)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (c000000000245750)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (c00000000024b554)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (c00000000031e8ac)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (c00000000033ab74)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffe0000ed708)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffe0000f14ee)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffe0000f8c62)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fd2c4)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffe00010256e)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffe00015160e)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (ffffffe000155148)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffe0001ae916)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffe0001c0c22)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffff810d9838)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ded75)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e8c42)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810ec917)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f2aae)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff8115eeb3)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (ffffffff81162517)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff811eb03f)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff811fdb98)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffff810c8218)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810cdd85)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810d8679)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810dc9b7)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e2bbe)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff81152143)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (ffffffff81155777)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff811dddef)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff811f08e8)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffff810d5b78)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810db0f5)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e57e9)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e9a47)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810efbde)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff8115cc83)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (ffffffff811602e7)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff811e8e0f)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff811fb968)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
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
In kernel/sched/cputime.c (ffffffff810e147d)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810e6dba)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810efb07)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f49fc)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810fac33)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff81169e10)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
```
```
In kernel/cgroup/freezer.c (ffffffff8116d657)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/bpf/helpers.c (ffffffff811f71bf)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff8120a51d)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
```
</details>
</li>
</ul>

## Differences
