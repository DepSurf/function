# Function: <code>uclamp_rq_inc_id</code>

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
In kernel/sched/core.c (ffffffff810d4082)
Location: kernel/sched/core.c:906
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:activate_task
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
In kernel/sched/core.c (ffffffff810de5c5)
Location: kernel/sched/core.c:944
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:uclamp_update_active_tasks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uclamp_rq_inc_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dbdf0)
Location: kernel/sched/core.c:964
Inline: False
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
ffffffff810dbdf0-ffffffff810dbf90: uclamp_rq_inc_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uclamp_rq_inc_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8490)
Location: kernel/sched/core.c:1123
Inline: False
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
ffffffff810d8490-ffffffff810d862f: uclamp_rq_inc_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uclamp_rq_inc_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810db4d0)
Location: kernel/sched/core.c:1136
Inline: False
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
ffffffff810db4d0-ffffffff810db713: uclamp_rq_inc_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uclamp_rq_inc_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ef400)
Location: kernel/sched/core.c:1490
Inline: False
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
ffffffff810ef400-ffffffff810ef729: uclamp_rq_inc_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uclamp_rq_inc_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110c700)
Location: kernel/sched/core.c:1533
Inline: False
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
ffffffff8110c700-ffffffff8110ca36: uclamp_rq_inc_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uclamp_rq_inc_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81132c70)
Location: kernel/sched/core.c:1521
Inline: False
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
ffffffff81132c70-ffffffff81132ffa: uclamp_rq_inc_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uclamp_rq_inc_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81141290)
Location: kernel/sched/core.c:1543
Inline: False
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
ffffffff81141290-ffffffff81141630: uclamp_rq_inc_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uclamp_rq_inc_id(struct rq *rq, struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114c4a0)
Location: kernel/sched/core.c:1584
Inline: False
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
ffffffff8114c4a0-ffffffff8114c840: uclamp_rq_inc_id (STB_LOCAL)
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
In kernel/sched/core.c (ffff8000101365b0)
Location: kernel/sched/core.c:944
Inline: True
Inline callers:
  - kernel/sched/core.c:enqueue_task
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
In kernel/sched/core.c (c0384bfc)
Location: kernel/sched/core.c:944
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:activate_task
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
In kernel/sched/core.c (c00000000018d1e0)
Location: kernel/sched/core.c:944
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:activate_task
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
In kernel/sched/core.c (ffffffff810d87b5)
Location: kernel/sched/core.c:944
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:activate_task
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
In kernel/sched/core.c (ffffffff810c71c5)
Location: kernel/sched/core.c:944
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:activate_task
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
In kernel/sched/core.c (ffffffff810e0393)
Location: kernel/sched/core.c:944
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:activate_task
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
