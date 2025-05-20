# Function: <code>task_group_is_autogroup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/auto_group.c (0)
Location: kernel/sched/auto_group.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/auto_group.c (0)
Location: kernel/sched/auto_group.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/auto_group.c (0)
Location: kernel/sched/auto_group.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.h:23
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.h:20
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
In kernel/sched/core.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.h:20
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
In kernel/sched/core.c (ffffffff810dbe0e)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:uclamp_rq_inc_id
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (ffffffff810e908f)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/autogroup.c (ffffffff811051b5)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:autogroup_path
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
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
In kernel/sched/core.c (ffffffff810d84b0)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:uclamp_rq_inc_id
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (ffffffff810e6e3f)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/autogroup.c (ffffffff81103835)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:autogroup_path
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
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
In kernel/sched/core.c (ffffffff810db51b)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:uclamp_rq_inc_id
```
```
In kernel/sched/fair.c (ffffffff810e8eef)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/autogroup.c (ffffffff81105b25)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:autogroup_path
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
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
In kernel/sched/core.c (ffffffff810ef471)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:uclamp_rq_inc_id
```
```
In kernel/sched/fair.c (ffffffff8110060f)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/autogroup.c (ffffffff811237b5)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:autogroup_path
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
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
In kernel/sched/core.c (ffffffff8110c771)
Location: kernel/sched/autogroup.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:uclamp_rq_inc_id
```
```
In kernel/sched/build_utility.c (ffffffff8114d272)
Location: kernel/sched/autogroup.h:23
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
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
In kernel/sched/core.c (ffffffff81132cd8)
Location: kernel/sched/autogroup.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:uclamp_rq_inc_id
```
```
In kernel/sched/build_utility.c (ffffffff8117c312)
Location: kernel/sched/autogroup.h:23
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
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
In kernel/sched/core.c (ffffffff811412f9)
Location: kernel/sched/autogroup.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:uclamp_rq_inc_id
```
```
In kernel/sched/build_utility.c (ffffffff8118cfbd)
Location: kernel/sched/autogroup.h:23
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
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
In kernel/sched/core.c (ffffffff8114c509)
Location: kernel/sched/autogroup.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:uclamp_rq_inc_id
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/build_utility.c (ffffffff8119b96d)
Location: kernel/sched/autogroup.h:23
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
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
In kernel/sched/core.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.h:20
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
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (c039107c)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/rt.c (c039f0f8)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/rt.c:print_rt_stats
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/autogroup.c (c03abf0c)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:autogroup_path
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
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
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_eff_value
```
```
In kernel/sched/fair.c (c000000000190bb8)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/rt.c (c0000000001a580c)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/rt.c:print_rt_stats
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/autogroup.c (c0000000001b4cd0)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:autogroup_path
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
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
In kernel/sched/core.c (ffffffe0000e7986)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffe0000eef6a)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/rt.c (ffffffe0000f9fd2)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/rt.c:print_rt_stats
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/autogroup.c (ffffffe000103918)
Location: kernel/sched/autogroup.h:20
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:autogroup_path
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
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
In kernel/sched/core.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.h:20
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
In kernel/sched/core.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.h:20
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
In kernel/sched/core.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.h:20
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
In kernel/sched/core.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.h:20
Inline: True
```
</details>
</li>
</ul>

## Differences
