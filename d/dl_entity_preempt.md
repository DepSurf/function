# Function: <code>dl_entity_preempt</code>

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
Location: kernel/sched/sched.h:125
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:125
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
Location: kernel/sched/sched.h:133
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:133
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
Location: kernel/sched/sched.h:140
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:140
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
Location: kernel/sched/sched.h:162
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:162
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
Location: kernel/sched/sched.h:163
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:163
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
In kernel/sched/core.c (ffffffff810c13a1)
Location: kernel/sched/sched.h:218
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810d48f5)
Location: kernel/sched/sched.h:218
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810ca70c)
Location: kernel/sched/sched.h:225
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810de325)
Location: kernel/sched/sched.h:225
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810d23bf)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810e541a)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810dc669)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810f083a)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810e53f8)
Location: kernel/sched/sched.h:231
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810fa1da)
Location: kernel/sched/sched.h:231
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
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
In kernel/sched/core.c (ffffffff810e2ea6)
Location: kernel/sched/sched.h:234
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810f862a)
Location: kernel/sched/sched.h:234
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
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
In kernel/sched/core.c (ffffffff810e4d71)
Location: kernel/sched/sched.h:243
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810fa78a)
Location: kernel/sched/sched.h:243
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
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
In kernel/sched/core.c (ffffffff810fbc51)
Location: kernel/sched/sched.h:245
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff8111553a)
Location: kernel/sched/sched.h:245
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
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
In kernel/sched/core.c (ffffffff811180e8)
Location: kernel/sched/sched.h:263
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/build_policy.c (ffffffff81134de9)
Location: kernel/sched/sched.h:263
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
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
In kernel/sched/core.c (ffffffff8113f723)
Location: kernel/sched/sched.h:264
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/build_policy.c (ffffffff8115f309)
Location: kernel/sched/sched.h:264
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
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
In kernel/sched/core.c (ffffffff8114bc75)
Location: kernel/sched/sched.h:263
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/build_policy.c (ffffffff8116f9f9)
Location: kernel/sched/sched.h:263
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
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
In kernel/sched/core.c (ffffffff81157a25)
Location: kernel/sched/sched.h:252
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/build_policy.c (ffffffff8117cf49)
Location: kernel/sched/sched.h:252
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:wakeup_preempt_dl
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
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
In kernel/sched/core.c (ffff80001013c348)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffff80001015243c)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (c038be10)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (c039f200)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
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
In kernel/sched/core.c (c00000000018a7d0)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (c0000000001a596c)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
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
In kernel/sched/core.c (ffffffe0000eb71a)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffe0000fa0d4)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810d689f)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810e9c3a)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810c5169)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810d9bfa)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810d366b)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810e6d6a)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810de437)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810f1cca)
Location: kernel/sched/sched.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
</details>
</li>
</ul>

## Differences
