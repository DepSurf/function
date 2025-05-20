# Function: <code>task_has_idle_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c68a2)
Location: kernel/sched/sched.h:181
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_load_weight
```
```
In kernel/sched/fair.c (ffffffff810d43e2)
Location: kernel/sched/sched.h:181
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
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
In kernel/sched/core.c (ffffffff810ccaae)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_load_weight
```
```
In kernel/sched/fair.c (ffffffff810db297)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
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
In kernel/sched/core.c (ffffffff810d263f)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/core.c:set_load_weight
```
```
In kernel/sched/fair.c (ffffffff810e51a7)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (ffffffff810e6c64)
Location: kernel/sched/sched.h:181
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ee70d)
Location: kernel/sched/sched.h:181
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (ffffffff81bdc47a)
Location: kernel/sched/sched.h:184
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ec54d)
Location: kernel/sched/sched.h:184
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (ffffffff81bce613)
Location: kernel/sched/sched.h:186
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810eeef0)
Location: kernel/sched/sched.h:186
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (ffffffff81ca5a38)
Location: kernel/sched/sched.h:186
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81104245)
Location: kernel/sched/sched.h:186
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (ffffffff8111171b)
Location: kernel/sched/sched.h:204
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
```
```
In kernel/sched/fair.c (ffffffff811224b0)
Location: kernel/sched/sched.h:204
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:sched_slice
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
In kernel/sched/core.c (ffffffff83ea8403)
Location: kernel/sched/sched.h:205
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
```
```
In kernel/sched/fair.c (ffffffff8114aa10)
Location: kernel/sched/sched.h:205
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:sched_slice
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
In kernel/sched/core.c (ffffffff836cccd3)
Location: kernel/sched/sched.h:205
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
```
```
In kernel/sched/fair.c (ffffffff8115c1f0)
Location: kernel/sched/sched.h:205
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:sched_slice
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
In kernel/sched/core.c (ffffffff838fe0b4)
Location: kernel/sched/sched.h:194
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
```
```
In kernel/sched/fair.c (ffffffff81167af0)
Location: kernel/sched/sched.h:194
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:check_preempt_wakeup_fair
  - kernel/sched/fair.c:check_preempt_wakeup_fair
  - kernel/sched/fair.c:check_preempt_wakeup_fair
  - kernel/sched/fair.c:check_preempt_wakeup_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffff800011444e1c)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffff800010144d28)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (c151ef28)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (c03913d8)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (c0000000013696f8)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (c000000000196350)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (ffffffe000006d3c)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffe0000ef8ee)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (ffffffff810cc9bf)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/core.c:set_load_weight
```
```
In kernel/sched/fair.c (ffffffff810df357)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (ffffffff810bb1bf)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/core.c:set_load_weight
```
```
In kernel/sched/fair.c (ffffffff810ce367)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (ffffffff810cbedf)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/core.c:set_load_weight
```
```
In kernel/sched/fair.c (ffffffff810db6d7)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (ffffffff810d44ef)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/core.c:set_load_weight
```
```
In kernel/sched/fair.c (ffffffff810e73c7)
Location: kernel/sched/sched.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
</details>
</li>
</ul>

## Differences
