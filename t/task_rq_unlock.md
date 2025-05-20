# Function: <code>task_rq_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void task_rq_unlock(struct rq *rq, struct task_struct *p, long unsigned int *flags);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a4900)
Location: kernel/sched/sched.h:1501
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_move_task
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810c286f)
Location: kernel/sched/sched.h:1501
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810a4900-ffffffff810a491c: task_rq_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void task_rq_unlock(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ac138)
Location: kernel/sched/sched.h:1484
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810c6220)
Location: kernel/sched/sched.h:1484
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810a8020-ffffffff810a803c: task_rq_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void task_rq_unlock(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2218)
Location: kernel/sched/sched.h:1523
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810cc1e5)
Location: kernel/sched/sched.h:1523
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810ae000-ffffffff810ae01c: task_rq_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void task_rq_unlock(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae310)
Location: kernel/sched/sched.h:1700
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810c6933)
Location: kernel/sched/sched.h:1700
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/livepatch/transition.c (0)
Location: kernel/sched/sched.h:1700
Inline: False
```
**Symbols:**

```
ffffffff810aaaa0-ffffffff810aaacc: task_rq_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void task_rq_unlock(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b55d0)
Location: kernel/sched/sched.h:1739
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810ce17b)
Location: kernel/sched/sched.h:1739
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/livepatch/transition.c (ffffffff8110373b)
Location: kernel/sched/sched.h:1739
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff810b17a0-ffffffff810b17cc: task_rq_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void task_rq_unlock(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bd280)
Location: kernel/sched/sched.h:1783
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/deadline.c (ffffffff810d7ff3)
Location: kernel/sched/sched.h:1783
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/livepatch/transition.c (ffffffff8110bb7f)
Location: kernel/sched/sched.h:1783
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff810bb7f0-ffffffff810bb81c: task_rq_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void task_rq_unlock(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7100)
Location: kernel/sched/sched.h:1120
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/deadline.c (ffffffff810df793)
Location: kernel/sched/sched.h:1120
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff810ef9e1)
Location: kernel/sched/sched.h:1120
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff8111736f)
Location: kernel/sched/sched.h:1120
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff810c5030-ffffffff810c505c: task_rq_unlock (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810cc560)
Location: kernel/sched/sched.h:1178
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/deadline.c (ffffffff810e6374)
Location: kernel/sched/sched.h:1178
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff810f6ea1)
Location: kernel/sched/sched.h:1178
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff81121705)
Location: kernel/sched/sched.h:1178
Inline: True
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
In kernel/sched/core.c (ffffffff810d7140)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/deadline.c (ffffffff810f460b)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff81102c31)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff8112dd25)
Location: kernel/sched/sched.h:1186
Inline: True
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
In kernel/sched/core.c (ffffffff810e1aa0)
Location: kernel/sched/sched.h:1234
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/deadline.c (ffffffff810fddfb)
Location: kernel/sched/sched.h:1234
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff8110dc11)
Location: kernel/sched/sched.h:1234
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff8113c388)
Location: kernel/sched/sched.h:1234
Inline: True
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
In kernel/sched/core.c (ffffffff810dee40)
Location: kernel/sched/sched.h:1292
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_sync_util_min_rt_default
```
```
In kernel/sched/deadline.c (ffffffff810fc3cb)
Location: kernel/sched/sched.h:1292
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff8110af65)
Location: kernel/sched/sched.h:1292
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff81136a98)
Location: kernel/sched/sched.h:1292
Inline: True
```
```
In fs/io-wq.c (ffffffff8139b406)
Location: kernel/sched/sched.h:1292
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void task_rq_unlock(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0a30)
Location: kernel/sched/sched.h:1305
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810fe7ad)
Location: kernel/sched/sched.h:1305
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff8110cb82)
Location: kernel/sched/sched.h:1305
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff81137831)
Location: kernel/sched/sched.h:1305
Inline: True
```
**Symbols:**

```
ffffffff810dd840-ffffffff810dd86c: task_rq_unlock (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810f5b40)
Location: kernel/sched/sched.h:1592
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/deadline.c (ffffffff8111a0da)
Location: kernel/sched/sched.h:1592
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff8112bbdf)
Location: kernel/sched/sched.h:1592
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/sched/core_sched.c (ffffffff8112c19a)
Location: kernel/sched/sched.h:1592
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_update_cookie
```
```
In kernel/livepatch/transition.c (ffffffff8115a588)
Location: kernel/sched/sched.h:1592
Inline: True
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
In kernel/sched/core.c (ffffffff81110630)
Location: kernel/sched/sched.h:1573
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/build_policy.c (ffffffff81139e22)
Location: kernel/sched/sched.h:1573
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
```
```
In kernel/sched/build_utility.c (ffffffff8114c3a6)
Location: kernel/sched/sched.h:1573
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:__sched_core_set
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
In kernel/sched/core.c (ffffffff811421c5)
Location: kernel/sched/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/build_policy.c (ffffffff8116468c)
Location: kernel/sched/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
```
```
In kernel/sched/build_utility.c (ffffffff8117af0a)
Location: kernel/sched/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:__sched_core_set
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
In kernel/sched/core.c (ffffffff8114dea6)
Location: kernel/sched/sched.h:1646
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/build_policy.c (ffffffff81174e2c)
Location: kernel/sched/sched.h:1646
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
```
```
In kernel/sched/build_utility.c (ffffffff8118ba6a)
Location: kernel/sched/sched.h:1646
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:__sched_core_set
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
In kernel/sched/core.c (ffffffff81159cd0)
Location: kernel/sched/sched.h:1665
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/build_policy.c (ffffffff8118312c)
Location: kernel/sched/sched.h:1665
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
```
```
In kernel/sched/build_utility.c (ffffffff8119a3ca)
Location: kernel/sched/sched.h:1665
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:__sched_core_set
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
In kernel/sched/core.c (ffff800010137c1c)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/deadline.c (ffff800010156aa4)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffff800010167a4c)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (c0384b64)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/cputime.c (c038f200)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/deadline.c (c03a4760)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (c03b48b8)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (c000000000181880)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/deadline.c (c0000000001ab4e0)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (c0000000001bf890)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (c0000000001f2c20)
Location: kernel/sched/sched.h:1186
Inline: True
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
In kernel/sched/core.c (ffffffe0000e7e40)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/deadline.c (ffffffe0000fdac0)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffe000109f90)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff810d0490)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/deadline.c (ffffffff810eda0b)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff810fbf41)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff81126305)
Location: kernel/sched/sched.h:1186
Inline: True
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
In kernel/sched/core.c (ffffffff810bfbd0)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/deadline.c (ffffffff810dda9b)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff810ec151)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff81118d65)
Location: kernel/sched/sched.h:1186
Inline: True
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
In kernel/sched/core.c (ffffffff810cf7d0)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/deadline.c (ffffffff810eab3b)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff810f9101)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff811241f5)
Location: kernel/sched/sched.h:1186
Inline: True
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
In kernel/sched/core.c (ffffffff810d7970)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/deadline.c (ffffffff810f5aeb)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff81104241)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff81130835)
Location: kernel/sched/sched.h:1186
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_flags *rf</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *flags</code>
</li>
</ul>
</details>
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
</ul>
