# Function: <code>activate_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aabc0)
Location: kernel/sched/core.c:846
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810aabc0-ffffffff810aac3d: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad800)
Location: kernel/sched/core.c:764
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810ad800-ffffffff810ad87d: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3900)
Location: kernel/sched/core.c:771
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810b3900-ffffffff810b397f: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af890)
Location: kernel/sched/core.c:776
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810af890-ffffffff810af947: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6c60)
Location: kernel/sched/core.c:786
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810b6c60-ffffffff810b6d1d: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810be7b0)
Location: kernel/sched/core.c:764
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810be7b0-ffffffff810be86f: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c79b0)
Location: kernel/sched/core.c:759
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810c79b0-ffffffff810c7ad5: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ce870)
Location: kernel/sched/core.c:1198
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810ce870-ffffffff810ceb59: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8560)
Location: kernel/sched/core.c:1318
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810d8560-ffffffff810d8920: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e4956)
Location: kernel/sched/core.c:1400
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810e23d0-ffffffff810e23ef: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2495)
Location: kernel/sched/core.c:1611
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810df7b0-ffffffff810df7cf: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e424a)
Location: kernel/sched/core.c:1621
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810e15a0-ffffffff810e15bf: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f94cf)
Location: kernel/sched/core.c:1999
Inline: True
Inline callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810f76b0-ffffffff810f76cf: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81115991)
Location: kernel/sched/core.c:2095
Inline: True
Inline callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff81113890-ffffffff811138b9: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113cd6e)
Location: kernel/sched/core.c:2083
Inline: True
Inline callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff8113aa20-ffffffff8113aa49: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115184f)
Location: kernel/sched/core.c:2105
Inline: True
Inline callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff8114e630-ffffffff8114e68a: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115d6e0)
Location: kernel/sched/core.c:2141
Inline: True
Inline callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
Direct callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff8115a490-ffffffff8115a4ea: activate_task (STB_GLOBAL)
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
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010138db0)
Location: kernel/sched/core.c:1318
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffff800010138db0-ffff800010138e20: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0387afc)
Location: kernel/sched/core.c:1318
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
c0387afc-c0387e54: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000184ba0)
Location: kernel/sched/core.c:1318
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/fair.c:attach_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
c000000000184ba0-c000000000184fc0: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e8962)
Location: kernel/sched/core.c:1318
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffe0000e8962-ffffffe0000e8a94: activate_task (STB_GLOBAL)
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
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2a20)
Location: kernel/sched/core.c:1318
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810d2a20-ffffffff810d2de2: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1060)
Location: kernel/sched/core.c:1318
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810c1060-ffffffff810c1420: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0570)
Location: kernel/sched/core.c:1318
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810d0570-ffffffff810d06c8: activate_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void activate_task(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da170)
Location: kernel/sched/core.c:1318
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810da170-ffffffff810da532: activate_task (STB_GLOBAL)
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
