# Function: <code>task_group</code>

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
In kernel/sched/core.c (ffffffff810ab310)
Location: kernel/sched/sched.h:923
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:init_idle
```
```
In kernel/sched/fair.c (ffffffff810b389a)
Location: kernel/sched/sched.h:923
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_move_group_fair
  - kernel/sched/fair.c:task_fork_fair
```
```
In kernel/sched/debug.c (0)
Location: kernel/sched/sched.h:923
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
In kernel/sched/core.c (ffffffff810b103d)
Location: kernel/sched/sched.h:959
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810bf2c8)
Location: kernel/sched/sched.h:959
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/debug.c (0)
Location: kernel/sched/sched.h:959
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
In kernel/sched/core.c (ffffffff810b72d2)
Location: kernel/sched/sched.h:989
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810c519c)
Location: kernel/sched/sched.h:989
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/debug.c (0)
Location: kernel/sched/sched.h:989
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
In kernel/sched/core.c (ffffffff810b35e2)
Location: kernel/sched/sched.h:1157
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810bee34)
Location: kernel/sched/sched.h:1157
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: kernel/sched/sched.h:1157
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
In kernel/sched/core.c (ffffffff810ba852)
Location: kernel/sched/sched.h:1175
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810c6614)
Location: kernel/sched/sched.h:1175
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: kernel/sched/sched.h:1175
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
In kernel/sched/core.c (ffffffff810c1cd2)
Location: kernel/sched/sched.h:1264
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810c582b)
Location: kernel/sched/sched.h:1264
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810def28)
Location: kernel/sched/sched.h:1264
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
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
In kernel/sched/core.c (ffffffff810cb002)
Location: kernel/sched/sched.h:1418
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810d23b1)
Location: kernel/sched/sched.h:1418
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810e96a8)
Location: kernel/sched/sched.h:1418
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
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
In kernel/sched/core.c (ffffffff810d2c95)
Location: kernel/sched/sched.h:1476
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810d9ff5)
Location: kernel/sched/sched.h:1476
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810f00ba)
Location: kernel/sched/sched.h:1476
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
In kernel/sched/core.c (ffffffff810de5d8)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (ffffffff810e5355)
Location: kernel/sched/sched.h:1490
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810ed7b8)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/debug.c (ffffffff810fbefa)
Location: kernel/sched/sched.h:1490
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
In kernel/sched/core.c (ffffffff810e5ce5)
Location: kernel/sched/sched.h:1530
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:uclamp_rq_inc_id
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (ffffffff810eddca)
Location: kernel/sched/sched.h:1530
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
```
```
In kernel/sched/debug.c (ffffffff81106647)
Location: kernel/sched/sched.h:1530
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
In kernel/sched/core.c (ffffffff810e3a33)
Location: kernel/sched/sched.h:1588
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:uclamp_rq_inc_id
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (ffffffff810ebbea)
Location: kernel/sched/sched.h:1588
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
```
```
In kernel/sched/debug.c (ffffffff81104c97)
Location: kernel/sched/sched.h:1588
Inline: True
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
In kernel/sched/core.c (ffffffff810e41d0)
Location: kernel/sched/sched.h:1599
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:uclamp_rq_inc_id
```
```
In kernel/sched/fair.c (ffffffff810ed74a)
Location: kernel/sched/sched.h:1599
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
```
```
In kernel/sched/debug.c (ffffffff8110704a)
Location: kernel/sched/sched.h:1599
Inline: True
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
In kernel/sched/core.c (ffffffff810faee0)
Location: kernel/sched/sched.h:1887
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:uclamp_rq_inc_id
```
```
In kernel/sched/fair.c (ffffffff8110645a)
Location: kernel/sched/sched.h:1887
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
```
```
In kernel/sched/debug.c (ffffffff8112503d)
Location: kernel/sched/sched.h:1887
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
In kernel/sched/core.c (ffffffff81117345)
Location: kernel/sched/sched.h:1887
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:uclamp_rq_inc_id
```
```
In kernel/sched/fair.c (ffffffff81122b19)
Location: kernel/sched/sched.h:1887
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:can_migrate_task
```
```
In kernel/sched/build_utility.c (ffffffff8114050f)
Location: kernel/sched/sched.h:1887
Inline: True
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
In kernel/sched/core.c (ffffffff83ea7d86)
Location: kernel/sched/sched.h:1936
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:uclamp_rq_inc_id
```
```
In kernel/sched/fair.c (ffffffff8114e585)
Location: kernel/sched/sched.h:1936
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
```
```
In kernel/sched/build_utility.c (ffffffff8116ac5b)
Location: kernel/sched/sched.h:1936
Inline: True
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
In kernel/sched/core.c (ffffffff836cc715)
Location: kernel/sched/sched.h:1979
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:uclamp_rq_inc_id
```
```
In kernel/sched/fair.c (ffffffff81154095)
Location: kernel/sched/sched.h:1979
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_is_throttled_fair
  - kernel/sched/fair.c:can_migrate_task
```
```
In kernel/sched/build_utility.c (ffffffff8117b36e)
Location: kernel/sched/sched.h:1979
Inline: True
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
In kernel/sched/core.c (ffffffff838fdad5)
Location: kernel/sched/sched.h:2021
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:uclamp_rq_inc_id
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (ffffffff811601e5)
Location: kernel/sched/sched.h:2021
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_is_throttled_fair
  - kernel/sched/fair.c:can_migrate_task
```
```
In kernel/sched/build_utility.c (ffffffff81188e2a)
Location: kernel/sched/sched.h:2021
Inline: True
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
In kernel/sched/core.c (ffff80001013cbe8)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:enqueue_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (ffff8000101411e8)
Location: kernel/sched/sched.h:1490
Inline: True
```
```
In kernel/sched/rt.c (ffff80001014e4ac)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/debug.c (ffff8000101607b4)
Location: kernel/sched/sched.h:1490
Inline: True
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
In kernel/sched/core.c (c0384c1c)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (c03971a0)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:can_migrate_task
```
```
In kernel/sched/rt.c (c039b7e8)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/debug.c (c03ad29c)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
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
In kernel/sched/core.c (c00000000018d224)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (c000000000194f00)
Location: kernel/sched/sched.h:1490
Inline: True
```
```
In kernel/sched/rt.c (c0000000001a123c)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/debug.c (c0000000001b6a74)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
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
In kernel/sched/core.c (ffffffe0000ec3ce)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffe0000ef7ee)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
```
```
In kernel/sched/rt.c (ffffffe0000f70c2)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/debug.c (ffffffe000104de8)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
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
In kernel/sched/core.c (ffffffff810d87c7)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (ffffffff810df505)
Location: kernel/sched/sched.h:1490
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810f522a)
Location: kernel/sched/sched.h:1490
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
In kernel/sched/core.c (ffffffff810c71d8)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (ffffffff810ce515)
Location: kernel/sched/sched.h:1490
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810d6ab8)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/debug.c (ffffffff810e53ea)
Location: kernel/sched/sched.h:1490
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
In kernel/sched/core.c (ffffffff810d3f55)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810db885)
Location: kernel/sched/sched.h:1490
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810e3ce8)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/debug.c (ffffffff810f242a)
Location: kernel/sched/sched.h:1490
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
In kernel/sched/core.c (ffffffff810e03a5)
Location: kernel/sched/sched.h:1490
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (ffffffff810e7575)
Location: kernel/sched/sched.h:1490
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810fd41a)
Location: kernel/sched/sched.h:1490
Inline: True
```
</details>
</li>
</ul>

## Differences
