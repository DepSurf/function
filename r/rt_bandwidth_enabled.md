# Function: <code>rt_bandwidth_enabled</code>

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
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:426
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:426
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
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:447
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:447
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
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:455
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:455
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
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:499
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:499
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
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:503
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:503
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
In kernel/sched/rt.c (ffffffff810d2f75)
Location: kernel/sched/sched.h:569
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810d7201)
Location: kernel/sched/sched.h:569
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff810dd1b5)
Location: kernel/sched/sched.h:579
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810e173f)
Location: kernel/sched/sched.h:579
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff810e4179)
Location: kernel/sched/sched.h:573
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810e8201)
Location: kernel/sched/sched.h:573
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/core.c (ffffffff810d6232)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (ffffffff810ed69f)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810f35d0)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff810f8310)
Location: kernel/sched/sched.h:589
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810fccce)
Location: kernel/sched/sched.h:589
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff810f6520)
Location: kernel/sched/sched.h:601
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810fb1e2)
Location: kernel/sched/sched.h:601
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff810f853d)
Location: kernel/sched/sched.h:610
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810fd418)
Location: kernel/sched/sched.h:610
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff81113b0c)
Location: kernel/sched/sched.h:627
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff811197f3)
Location: kernel/sched/sched.h:627
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81136253)
Location: kernel/sched/sched.h:622
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81160833)
Location: kernel/sched/sched.h:652
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81170f5b)
Location: kernel/sched/sched.h:649
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117e680)
Location: kernel/sched/sched.h:678
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl_se
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
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
In kernel/sched/core.c (ffff800010136bf0)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (ffff80001014e380)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffff8000101557e4)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/core.c (c03855cc)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (c039b69c)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (c03a31b8)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/core.c (c000000000181a90)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (c0000000001a1160)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (c0000000001a99ec)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/core.c (ffffffe0000e7506)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (ffffffe0000f706e)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffe0000fd352)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff810e8567)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810ec9d0)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/core.c (ffffffff810be763)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (ffffffff810d699f)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810dca70)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/core.c (ffffffff810ce9f0)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (ffffffff810e3bcf)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810e9b00)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff810f12c7)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810f4aba)
Location: kernel/sched/sched.h:580
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
</details>
</li>
</ul>

## Differences
