# Function: <code>task_current</code>

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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1025
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1025
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1025
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1063
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1063
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1063
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1097
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1097
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1097
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1265
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1265
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1265
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1302
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1302
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1302
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1391
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1391
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1391
Inline: True
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1545
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1545
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1545
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1603
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1603
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1603
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
Location: kernel/sched/sched.h:1617
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1617
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1617
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
In kernel/sched/core.c (ffffffff810e69d8)
Location: kernel/sched/sched.h:1657
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/rt.c (ffffffff810f7248)
Location: kernel/sched/sched.h:1657
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810f9d21)
Location: kernel/sched/sched.h:1657
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/psi.c (ffffffff8110dc6d)
Location: kernel/sched/sched.h:1657
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff810e48d8)
Location: kernel/sched/sched.h:1722
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/rt.c (ffffffff810f53d8)
Location: kernel/sched/sched.h:1722
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810f80e1)
Location: kernel/sched/sched.h:1722
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/psi.c (ffffffff8110afbf)
Location: kernel/sched/sched.h:1722
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff810e6898)
Location: kernel/sched/sched.h:1733
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff810e8e75)
Location: kernel/sched/sched.h:1733
Inline: True
Inline callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
```
In kernel/sched/rt.c (ffffffff810f74a8)
Location: kernel/sched/sched.h:1733
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa241)
Location: kernel/sched/sched.h:1733
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/debug.c (0)
Location: kernel/sched/sched.h:1733
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
In kernel/sched/core.c (ffffffff810fddea)
Location: kernel/sched/sched.h:2021
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff811007de)
Location: kernel/sched/sched.h:2021
Inline: True
Inline callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
```
In kernel/sched/rt.c (ffffffff81111a18)
Location: kernel/sched/sched.h:2021
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/sched/deadline.c (ffffffff81115081)
Location: kernel/sched/sched.h:2021
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/debug.c (0)
Location: kernel/sched/sched.h:2021
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
In kernel/sched/core.c (ffffffff8111a86a)
Location: kernel/sched/sched.h:2016
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff811228d2)
Location: kernel/sched/sched.h:2016
Inline: True
Inline callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
```
In kernel/sched/build_policy.c (ffffffff8112dfd1)
Location: kernel/sched/sched.h:2016
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:enqueue_task_rt
```
```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/sched.h:2016
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
In kernel/sched/core.c (ffffffff8114215c)
Location: kernel/sched/sched.h:2066
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff8114a622)
Location: kernel/sched/sched.h:2066
Inline: True
Inline callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
```
In kernel/sched/build_policy.c (ffffffff81157dc1)
Location: kernel/sched/sched.h:2066
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:enqueue_task_rt
```
```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/sched.h:2066
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
In kernel/sched/core.c (ffffffff8114de4e)
Location: kernel/sched/sched.h:2109
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff8115ac92)
Location: kernel/sched/sched.h:2109
Inline: True
Inline callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
```
In kernel/sched/build_policy.c (ffffffff81167ec1)
Location: kernel/sched/sched.h:2109
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:enqueue_task_rt
```
```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/sched.h:2109
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
In kernel/sched/core.c (ffffffff81159c76)
Location: kernel/sched/sched.h:2151
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff8115ee47)
Location: kernel/sched/sched.h:2151
Inline: True
Inline callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
```
In kernel/sched/build_policy.c (ffffffff81174cc1)
Location: kernel/sched/sched.h:2151
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:enqueue_task_rt
```
```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/sched.h:2151
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1617
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1617
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1617
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
In kernel/sched/core.c (c038de68)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/rt.c (c039b438)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/sched/deadline.c (c039f1a0)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (c00000000018cf9c)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/rt.c (c0000000001a0c10)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/sched/deadline.c (c0000000001a58dc)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (ffffffe0000eccee)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/rt.c (ffffffe0000f6cfc)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fa06e)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_task_dl
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
Location: kernel/sched/sched.h:1617
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1617
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1617
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
Location: kernel/sched/sched.h:1617
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1617
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1617
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
Location: kernel/sched/sched.h:1617
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1617
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1617
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
Location: kernel/sched/sched.h:1617
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1617
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1617
Inline: True
```
</details>
</li>
</ul>

## Differences
