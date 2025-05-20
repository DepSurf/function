# Function: <code>resched_curr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa2d0)
Location: kernel/sched/core.c:574
Inline: False
Direct callers:
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:yield_to
  - kernel/sched/idle_task.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810aa2d0-ffffffff810aa38b: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810acf30)
Location: kernel/sched/core.c:481
Inline: False
Direct callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle_task.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810acf30-ffffffff810acfe5: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2fc0)
Location: kernel/sched/core.c:481
Inline: False
Direct callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle_task.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810b2fc0-ffffffff810b3070: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aeee0)
Location: kernel/sched/core.c:479
Inline: False
Direct callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle_task.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810aeee0-ffffffff810aef94: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6130)
Location: kernel/sched/core.c:481
Inline: False
Direct callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle_task.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810b6130-ffffffff810b61ed: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bdf90)
Location: kernel/sched/core.c:459
Inline: False
Direct callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810bdf90-ffffffff810be049: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7240)
Location: kernel/sched/core.c:465
Inline: False
Direct callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810c7240-ffffffff810c72f9: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cd7a0)
Location: kernel/sched/core.c:507
Inline: False
Direct callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810cd7a0-ffffffff810cd85e: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d72d0)
Location: kernel/sched/core.c:507
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810d72d0-ffffffff810d738e: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1d40)
Location: kernel/sched/core.c:510
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810e1d40-ffffffff810e1dfe: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df120)
Location: kernel/sched/core.c:599
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810df120-ffffffff810df1bb: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0db0)
Location: kernel/sched/core.c:609
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810e0db0-ffffffff810e0e4b: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f5cf0)
Location: kernel/sched/core.c:961
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/core_sched.c:sched_core_update_cookie
```
**Symbols:**

```
ffffffff810f5cf0-ffffffff810f5d88: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81110e50)
Location: kernel/sched/core.c:1031
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:check_preempt_curr_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:__disable_runtime
  - kernel/sched/build_policy.c:check_preempt_curr_idle
  - kernel/sched/build_utility.c:__sched_core_set
```
**Symbols:**

```
ffffffff81110e50-ffffffff81110f47: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81137e00)
Location: kernel/sched/core.c:1019
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:check_preempt_curr_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:__disable_runtime
  - kernel/sched/build_policy.c:check_preempt_curr_idle
  - kernel/sched/build_utility.c:__sched_core_set
```
**Symbols:**

```
ffffffff81137e00-ffffffff81137ef5: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81146f20)
Location: kernel/sched/core.c:1041
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:check_preempt_curr_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:__disable_runtime
  - kernel/sched/build_policy.c:check_preempt_curr_idle
  - kernel/sched/build_utility.c:__sched_core_set
```
**Symbols:**

```
ffffffff81146f20-ffffffff81147068: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81152750)
Location: kernel/sched/core.c:1041
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:wakeup_preempt
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup_fair
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:update_curr
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:wakeup_preempt_dl
  - kernel/sched/build_policy.c:update_curr_dl_se
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:wakeup_preempt_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:__disable_runtime
  - kernel/sched/build_policy.c:wakeup_preempt_idle
  - kernel/sched/build_utility.c:__sched_core_set
```
**Symbols:**

```
ffffffff81152750-ffffffff81152898: resched_curr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010137e40)
Location: kernel/sched/core.c:507
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffff800010137e40-ffff800010137ec8: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0386878)
Location: kernel/sched/core.c:507
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
c0386878-c03868d8: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000183330)
Location: kernel/sched/core.c:507
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
c000000000183330-c000000000183490: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e8020)
Location: kernel/sched/core.c:507
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffe0000e8020-ffffffe0000e807a: resched_curr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d17a0)
Location: kernel/sched/core.c:507
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810d17a0-ffffffff810d185e: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bfd60)
Location: kernel/sched/core.c:507
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810bfd60-ffffffff810bfe1e: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf960)
Location: kernel/sched/core.c:507
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810cf960-ffffffff810cfa1e: resched_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void resched_curr(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8e80)
Location: kernel/sched/core.c:507
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/idle.c:check_preempt_curr_idle
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810d8e80-ffffffff810d8f57: resched_curr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
