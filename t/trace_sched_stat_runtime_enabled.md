# Function: <code>trace_sched_stat_runtime_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bb93f)
Location: include/trace/events/sched.h:406
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810c1f28)
Location: include/trace/events/sched.h:406
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810bcabd)
Location: include/trace/events/sched.h:407
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810c46c2)
Location: include/trace/events/sched.h:413
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810cc0c5)
Location: include/trace/events/sched.h:413
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810d4825)
Location: include/trace/events/sched.h:428
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dcc64)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e7094)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f1fca)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f0113)
Location: include/trace/events/sched.h:519
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f18e3)
Location: include/trace/events/sched.h:519
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110b41c)
Location: include/trace/events/sched.h:517
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff81126e8b)
Location: include/trace/events/sched.h:520
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8112eb0a)
Location: include/trace/events/sched.h:520
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
In kernel/sched/fair.c (ffffffff8115033d)
Location: include/trace/events/sched.h:520
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8115fe05)
Location: include/trace/events/sched.h:520
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_rt
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
In kernel/sched/fair.c (ffffffff8115f1d1)
Location: include/trace/events/sched.h:520
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff81170515)
Location: include/trace/events/sched.h:520
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_rt
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
In kernel/sched/fair.c (ffffffff8116d742)
Location: include/trace/events/sched.h:517
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8117de66)
Location: include/trace/events/sched.h:517
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_rt
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010146fb0)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c03952a8)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0000000001985f4)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f2852)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e1244)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d0324)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dd5c4)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9344)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
</ul>

## Differences
