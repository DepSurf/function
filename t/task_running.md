# Function: <code>task_running</code>

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
In kernel/sched/core.c (ffffffff810ac01c)
Location: kernel/sched/sched.h:1030
Inline: True
Inline callers:
  - kernel/sched/core.c:wait_task_inactive
```
```
In kernel/sched/fair.c (ffffffff810b3024)
Location: kernel/sched/sched.h:1030
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1030
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1030
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
In kernel/sched/core.c (ffffffff810aec64)
Location: kernel/sched/sched.h:1068
Inline: True
Inline callers:
  - kernel/sched/core.c:wait_task_inactive
```
```
In kernel/sched/fair.c (ffffffff810b5beb)
Location: kernel/sched/sched.h:1068
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1068
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1068
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
In kernel/sched/core.c (ffffffff810b4d95)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/core.c:wait_task_inactive
```
```
In kernel/sched/fair.c (ffffffff810bbbdb)
Location: kernel/sched/sched.h:1102
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1102
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1102
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
In kernel/sched/core.c (ffffffff810b0e69)
Location: kernel/sched/sched.h:1270
Inline: True
Inline callers:
  - kernel/sched/core.c:wait_task_inactive
```
```
In kernel/sched/fair.c (ffffffff810b6851)
Location: kernel/sched/sched.h:1270
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1270
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1270
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: kernel/sched/sched.h:1270
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
In kernel/sched/core.c (ffffffff810b82ac)
Location: kernel/sched/sched.h:1307
Inline: True
Inline callers:
  - kernel/sched/core.c:wait_task_inactive
```
```
In kernel/sched/fair.c (ffffffff810bda4f)
Location: kernel/sched/sched.h:1307
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1307
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1307
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: kernel/sched/sched.h:1307
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
In kernel/sched/core.c (ffffffff819ece04)
Location: kernel/sched/sched.h:1396
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810c58d8)
Location: kernel/sched/sched.h:1396
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810d3e17)
Location: kernel/sched/sched.h:1396
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810d5e72)
Location: kernel/sched/sched.h:1396
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
```
```
In kernel/livepatch/transition.c (ffffffff8110bad1)
Location: kernel/sched/sched.h:1396
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
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
In kernel/sched/core.c (ffffffff81a2803e)
Location: kernel/sched/sched.h:1550
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810d2470)
Location: kernel/sched/sched.h:1550
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810ddab7)
Location: kernel/sched/sched.h:1550
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810dfd42)
Location: kernel/sched/sched.h:1550
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
```
```
In kernel/livepatch/transition.c (ffffffff811172c1)
Location: kernel/sched/sched.h:1550
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
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
In kernel/sched/core.c (ffffffff81a987bd)
Location: kernel/sched/sched.h:1608
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810da0ce)
Location: kernel/sched/sched.h:1608
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810e4ab2)
Location: kernel/sched/sched.h:1608
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810e6777)
Location: kernel/sched/sched.h:1608
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
```
```
In kernel/livepatch/transition.c (ffffffff81121578)
Location: kernel/sched/sched.h:1608
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
In kernel/sched/core.c (ffffffff81ad010d)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810e542e)
Location: kernel/sched/sched.h:1622
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810efc82)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810f2004)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
```
```
In kernel/livepatch/transition.c (ffffffff8112db98)
Location: kernel/sched/sched.h:1622
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
In kernel/sched/core.c (ffffffff81bc8b26)
Location: kernel/sched/sched.h:1662
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810f11fb)
Location: kernel/sched/sched.h:1662
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810f9475)
Location: kernel/sched/sched.h:1662
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_lock_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810fc46b)
Location: kernel/sched/sched.h:1662
Inline: True
Inline callers:
  - kernel/sched/deadline.c:find_lock_later_rq
```
```
In kernel/livepatch/transition.c (ffffffff8113c360)
Location: kernel/sched/sched.h:1662
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
In kernel/sched/core.c (ffffffff81c418fc)
Location: kernel/sched/sched.h:1727
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff810ee68b)
Location: kernel/sched/sched.h:1727
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810f7765)
Location: kernel/sched/sched.h:1727
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_lock_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810fad58)
Location: kernel/sched/sched.h:1727
Inline: True
Inline callers:
  - kernel/sched/deadline.c:find_lock_later_rq
```
```
In kernel/livepatch/transition.c (ffffffff81136a70)
Location: kernel/sched/sched.h:1727
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
In kernel/sched/core.c (ffffffff81c33869)
Location: kernel/sched/sched.h:1738
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff810f2352)
Location: kernel/sched/sched.h:1738
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810f9c75)
Location: kernel/sched/sched.h:1738
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_lock_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810fdaf7)
Location: kernel/sched/sched.h:1738
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
```
```
In kernel/livepatch/transition.c (ffffffff811376bc)
Location: kernel/sched/sched.h:1738
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
In kernel/sched/core.c (ffffffff81d521ad)
Location: kernel/sched/sched.h:2026
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff811099bf)
Location: kernel/sched/sched.h:2026
Inline: True
```
```
In kernel/sched/rt.c (ffffffff81112bc5)
Location: kernel/sched/sched.h:2026
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_lock_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff81115fcf)
Location: kernel/sched/sched.h:2026
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
```
```
In kernel/sched/core_sched.c (ffffffff8112c196)
Location: kernel/sched/sched.h:2026
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_update_cookie
```
```
In kernel/livepatch/transition.c (ffffffff8115a560)
Location: kernel/sched/sched.h:2026
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
In kernel/sched/core.c (ffffffff81f22878)
Location: kernel/sched/sched.h:2021
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff811253ef)
Location: kernel/sched/sched.h:2021
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
```
```
In kernel/sched/build_policy.c (ffffffff8112fc17)
Location: kernel/sched/sched.h:2021
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
```
In kernel/sched/build_utility.c (ffffffff811449ed)
Location: kernel/sched/sched.h:2021
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_set
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/sched/core.c (ffff800010da1e88)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffff8000101412dc)
Location: kernel/sched/sched.h:1622
Inline: True
```
```
In kernel/sched/rt.c (ffff8000101510a8)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffff800010153b78)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
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
In kernel/sched/core.c (c0e99f88)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (c0391380)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
```
```
In kernel/sched/rt.c (c039c34c)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (c039feb0)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
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
In kernel/sched/core.c (c000000000ee3200)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (c000000000195068)
Location: kernel/sched/sched.h:1622
Inline: True
```
```
In kernel/sched/rt.c (c0000000001a1f90)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (c0000000001a69c0)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
```
```
In kernel/livepatch/transition.c (c0000000001f2a28)
Location: kernel/sched/sched.h:1622
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
In kernel/sched/core.c (ffffffe0008c55b8)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffe0000ef8be)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
```
```
In kernel/sched/rt.c (ffffffe0000f9366)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffe0000fb8b0)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
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
In kernel/sched/core.c (ffffffff81a6ef7d)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810df5de)
Location: kernel/sched/sched.h:1622
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810e9572)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810eb404)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
```
```
In kernel/livepatch/transition.c (ffffffff81126178)
Location: kernel/sched/sched.h:1622
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
In kernel/sched/core.c (ffffffff81a2b344)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810ce5ee)
Location: kernel/sched/sched.h:1622
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810d903d)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810db41f)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
```
```
In kernel/livepatch/transition.c (ffffffff81118bd8)
Location: kernel/sched/sched.h:1622
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
In kernel/sched/core.c (ffffffff81adb38d)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810db95e)
Location: kernel/sched/sched.h:1622
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810e61b2)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810e8534)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
```
```
In kernel/livepatch/transition.c (ffffffff81124068)
Location: kernel/sched/sched.h:1622
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
In kernel/sched/core.c (ffffffff81ae7892)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810e764e)
Location: kernel/sched/sched.h:1622
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810efeab)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810f2855)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
```
```
In kernel/livepatch/transition.c (ffffffff811306a8)
Location: kernel/sched/sched.h:1622
Inline: True
```
</details>
</li>
</ul>

## Differences
