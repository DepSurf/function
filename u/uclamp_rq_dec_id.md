# Function: <code>uclamp_rq_dec_id</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3fba)
Location: kernel/sched/core.c:944
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:deactivate_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de4f8)
Location: kernel/sched/core.c:982
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_update_active_tasks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void uclamp_rq_dec_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dcb40)
Location: kernel/sched/core.c:1002
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:uclamp_update_active_tasks
```
**Symbols:**

```
ffffffff810dcb40-ffffffff810dccc6: uclamp_rq_dec_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void uclamp_rq_dec_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d93b0)
Location: kernel/sched/core.c:1161
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:uclamp_update_active_tasks
```
**Symbols:**

```
ffffffff810d93b0-ffffffff810d9536: uclamp_rq_dec_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void uclamp_rq_dec_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dad40)
Location: kernel/sched/core.c:1174
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_update_active_tasks
```
**Symbols:**

```
ffffffff810dad40-ffffffff810daec2: uclamp_rq_dec_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uclamp_rq_dec_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810eeabe)
Location: kernel/sched/core.c:1528
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_update_active_tasks
```
**Symbols:**

```
ffffffff810ee9c0-ffffffff810eebc7: uclamp_rq_dec_id (STB_LOCAL)
ffffffff81ca5b1f-ffffffff81ca5b7f: uclamp_rq_dec_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uclamp_rq_dec_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff8110b830)
Location: kernel/sched/core.c:1571
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_update_active_tasks
```
**Symbols:**

```
ffffffff8110b720-ffffffff8110b935: uclamp_rq_dec_id (STB_LOCAL)
ffffffff81e55453-ffffffff81e554b3: uclamp_rq_dec_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uclamp_rq_dec_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81131b96)
Location: kernel/sched/core.c:1559
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_update_active_tasks
```
**Symbols:**

```
ffffffff81131a70-ffffffff81131cd9: uclamp_rq_dec_id (STB_LOCAL)
ffffffff820568f7-ffffffff82056957: uclamp_rq_dec_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uclamp_rq_dec_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff8113fdf0)
Location: kernel/sched/core.c:1581
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_update_active_tasks
```
**Symbols:**

```
ffffffff8113fcc0-ffffffff8113ff47: uclamp_rq_dec_id (STB_LOCAL)
ffffffff820d4fba-ffffffff820d501a: uclamp_rq_dec_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uclamp_rq_dec_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff8114ad50)
Location: kernel/sched/core.c:1622
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_update_active_tasks
```
**Symbols:**

```
ffffffff8114ac20-ffffffff8114aea7: uclamp_rq_dec_id (STB_LOCAL)
ffffffff821afe93-ffffffff821afef3: uclamp_rq_dec_id.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013687c)
Location: kernel/sched/core.c:982
Inline: True
Inline callers:
  - kernel/sched/core.c:dequeue_task
  - kernel/sched/core.c:dequeue_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_update_active_tasks
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0384ba0)
Location: kernel/sched/core.c:982
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:deactivate_task
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018d110)
Location: kernel/sched/core.c:982
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_update_active_tasks
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d86e8)
Location: kernel/sched/core.c:982
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_update_active_tasks
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c70f8)
Location: kernel/sched/core.c:982
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_update_active_tasks
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e02c6)
Location: kernel/sched/core.c:982
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_update_active_tasks
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
