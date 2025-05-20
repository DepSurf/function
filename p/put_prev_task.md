# Function: <code>put_prev_task</code>

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
In kernel/sched/core.c (ffffffff810a9e3a)
Location: kernel/sched/sched.h:1233
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_move_task
```
```
In kernel/sched/idle_task.c (ffffffff810b1c66)
Location: kernel/sched/sched.h:1233
Inline: True
Inline callers:
  - kernel/sched/idle_task.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810bdba1)
Location: kernel/sched/sched.h:1233
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c0000)
Location: kernel/sched/sched.h:1233
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c2dcc)
Location: kernel/sched/sched.h:1233
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810c3052)
Location: kernel/sched/sched.h:1233
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810b32cc)
Location: kernel/sched/sched.h:1258
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle_task.c (ffffffff810b4785)
Location: kernel/sched/sched.h:1258
Inline: True
Inline callers:
  - kernel/sched/idle_task.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810c13b1)
Location: kernel/sched/sched.h:1258
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c3a20)
Location: kernel/sched/sched.h:1258
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c675c)
Location: kernel/sched/sched.h:1258
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810c69de)
Location: kernel/sched/sched.h:1258
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810b98be)
Location: kernel/sched/sched.h:1292
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle_task.c (ffffffff810badb5)
Location: kernel/sched/sched.h:1292
Inline: True
Inline callers:
  - kernel/sched/idle_task.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810c73ae)
Location: kernel/sched/sched.h:1292
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c9a90)
Location: kernel/sched/sched.h:1292
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cc74c)
Location: kernel/sched/sched.h:1292
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810cc9be)
Location: kernel/sched/sched.h:1292
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810b4412)
Location: kernel/sched/sched.h:1462
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle_task.c (ffffffff810b5655)
Location: kernel/sched/sched.h:1462
Inline: True
Inline callers:
  - kernel/sched/idle_task.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810c0f82)
Location: kernel/sched/sched.h:1462
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c4c10)
Location: kernel/sched/sched.h:1462
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810c80f2)
Location: kernel/sched/sched.h:1462
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810cd8c3)
Location: kernel/sched/sched.h:1462
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810bb6c6)
Location: kernel/sched/sched.h:1499
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle_task.c (ffffffff810bc9a5)
Location: kernel/sched/sched.h:1499
Inline: True
Inline callers:
  - kernel/sched/idle_task.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810c88ed)
Location: kernel/sched/sched.h:1499
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810cc2c0)
Location: kernel/sched/sched.h:1499
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810cf8d2)
Location: kernel/sched/sched.h:1499
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810d5113)
Location: kernel/sched/sched.h:1499
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810c2bc6)
Location: kernel/sched/sched.h:1540
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle.c (ffffffff810c4055)
Location: kernel/sched/sched.h:1540
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810d0e9f)
Location: kernel/sched/sched.h:1540
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810d3fde)
Location: kernel/sched/sched.h:1540
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810d748c)
Location: kernel/sched/sched.h:1540
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810dd0e7)
Location: kernel/sched/sched.h:1540
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810cbec6)
Location: kernel/sched/sched.h:1694
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle.c (ffffffff810cd355)
Location: kernel/sched/sched.h:1694
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810da72b)
Location: kernel/sched/sched.h:1694
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810ddc7e)
Location: kernel/sched/sched.h:1694
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e1a4c)
Location: kernel/sched/sched.h:1694
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e6d47)
Location: kernel/sched/sched.h:1694
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810d3f6e)
Location: kernel/sched/sched.h:1756
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle.c (ffffffff810d5715)
Location: kernel/sched/sched.h:1756
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810e1a1b)
Location: kernel/sched/sched.h:1756
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810e4c85)
Location: kernel/sched/sched.h:1756
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e852c)
Location: kernel/sched/sched.h:1756
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810ed9d7)
Location: kernel/sched/sched.h:1756
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810de48e)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle.c (ffffffff810dfd2c)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810ec561)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff810e6b77)
Location: kernel/sched/sched.h:1803
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff810f615c)
Location: kernel/sched/sched.h:1803
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff810e4a8d)
Location: kernel/sched/sched.h:1877
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff810f42b2)
Location: kernel/sched/sched.h:1877
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff810e6a4d)
Location: kernel/sched/sched.h:1888
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff810f5c12)
Location: kernel/sched/sched.h:1888
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff810fdfff)
Location: kernel/sched/sched.h:2179
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:put_prev_task_balance
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff8110f945)
Location: kernel/sched/sched.h:2179
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff8111aa76)
Location: kernel/sched/sched.h:2173
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:put_prev_task_balance
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff8112b935)
Location: kernel/sched/sched.h:2173
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff81142287)
Location: kernel/sched/sched.h:2224
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:put_prev_task_balance
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff8115530d)
Location: kernel/sched/sched.h:2224
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff8114df83)
Location: kernel/sched/sched.h:2271
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:put_prev_task_balance
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff811654bd)
Location: kernel/sched/sched.h:2271
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff81159dbd)
Location: kernel/sched/sched.h:2323
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:__do_set_cpus_allowed
```
```
In kernel/sched/fair.c (ffffffff81172208)
Location: kernel/sched/sched.h:2323
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_prev_task(struct rq *rq, struct task_struct *prev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013e060)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:do_set_cpus_allowed
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffff80001013f8f0)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffff80001014ca4c)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffff800010132518-ffff800010132558: put_prev_task (STB_LOCAL)
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
In kernel/sched/core.c (c038e208)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle.c (c038f804)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (c039a740)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (c00000000018d390)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle.c (c00000000018ea00)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (c00000000019f5d4)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffe0000ecda4)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle.c (ffffffe0000edd2e)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffe0000f5f54)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff810d867e)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle.c (ffffffff810d9f1c)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810e66c1)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff810c708e)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle.c (ffffffff810c8f0c)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810d5861)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff810d4e26)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle.c (ffffffff810d625c)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810e2a91)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff810e025c)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/idle.c (ffffffff810e1b6c)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
```
In kernel/sched/fair.c (ffffffff810ee661)
Location: kernel/sched/sched.h:1774
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
