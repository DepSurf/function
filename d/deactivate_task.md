# Function: <code>deactivate_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aac40)
Location: kernel/sched/core.c:854
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810aac40-ffffffff810aace0: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad880)
Location: kernel/sched/core.c:772
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810ad880-ffffffff810ad91b: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3980)
Location: kernel/sched/core.c:779
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810b3980-ffffffff810b3a1d: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af950)
Location: kernel/sched/core.c:784
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810af950-ffffffff810afa25: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6d20)
Location: kernel/sched/core.c:794
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810b6d20-ffffffff810b6dfb: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810be870)
Location: kernel/sched/core.c:772
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810be870-ffffffff810be953: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7ae0)
Location: kernel/sched/core.c:767
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810c7ae0-ffffffff810c7bfb: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ceb60)
Location: kernel/sched/core.c:1208
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810ceb60-ffffffff810cee9a: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8920)
Location: kernel/sched/core.c:1328
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810d8920-ffffffff810d8c5a: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81bc8558)
Location: kernel/sched/core.c:1407
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
Direct callers:
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_one_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810e23f0-ffffffff810e240d: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81c412a1)
Location: kernel/sched/core.c:1618
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_one_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810df7d0-ffffffff810df7ed: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81c33207)
Location: kernel/sched/core.c:1628
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810e15c0-ffffffff810e15dc: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81d51bfb)
Location: kernel/sched/core.c:2006
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810f76d0-ffffffff810f76ec: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81f2213c)
Location: kernel/sched/core.c:2102
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff811138c0-ffffffff811138e8: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff820cca3e)
Location: kernel/sched/core.c:2090
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff8113aa60-ffffffff8113aa88: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82150d10)
Location: kernel/sched/core.c:2117
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff81149dc0-ffffffff81149de8: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82233b3c)
Location: kernel/sched/core.c:2154
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff811558c0-ffffffff811558e8: deactivate_task (STB_GLOBAL)
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
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010138e20)
Location: kernel/sched/core.c:1328
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffff800010138e20-ffff800010138e98: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0387e54)
Location: kernel/sched/core.c:1328
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
c0387e54-c03881f4: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000184fc0)
Location: kernel/sched/core.c:1328
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
c000000000184fc0-c0000000001853d0: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e8a94)
Location: kernel/sched/core.c:1328
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffe0000e8a94-ffffffe0000e8bdc: deactivate_task (STB_GLOBAL)
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
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2df0)
Location: kernel/sched/core.c:1328
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810d2df0-ffffffff810d312a: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1420)
Location: kernel/sched/core.c:1328
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810c1420-ffffffff810c175a: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d06d0)
Location: kernel/sched/core.c:1328
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810d06d0-ffffffff810d080f: deactivate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void deactivate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da540)
Location: kernel/sched/core.c:1328
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810da540-ffffffff810da87a: deactivate_task (STB_GLOBAL)
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
