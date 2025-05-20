# Function: <code>trace_sched_stat_sleep_enabled</code>

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
In kernel/sched/fair.c (ffffffff810bb930)
Location: include/trace/events/sched.h:357
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
In kernel/sched/fair.c (ffffffff810c1f19)
Location: include/trace/events/sched.h:357
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
In kernel/sched/fair.c (ffffffff810bcaae)
Location: include/trace/events/sched.h:358
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
In kernel/sched/fair.c (ffffffff810c46b3)
Location: include/trace/events/sched.h:364
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
In kernel/sched/fair.c (ffffffff810cc0b6)
Location: include/trace/events/sched.h:364
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
In kernel/sched/fair.c (ffffffff810d4816)
Location: include/trace/events/sched.h:379
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
In kernel/sched/fair.c (ffffffff810dcc55)
Location: include/trace/events/sched.h:386
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
In kernel/sched/fair.c (ffffffff810e7085)
Location: include/trace/events/sched.h:386
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
In kernel/sched/fair.c (ffffffff810f1fbb)
Location: include/trace/events/sched.h:386
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
In kernel/sched/fair.c (ffffffff810f0104)
Location: include/trace/events/sched.h:470
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
In kernel/sched/fair.c (ffffffff810f18d4)
Location: include/trace/events/sched.h:470
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
In kernel/sched/fair.c (ffffffff8110b416)
Location: include/trace/events/sched.h:468
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
In kernel/sched/fair.c (ffffffff81126e85)
Location: include/trace/events/sched.h:471
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8112eb04)
Location: include/trace/events/sched.h:471
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
In kernel/sched/fair.c (ffffffff81150337)
Location: include/trace/events/sched.h:471
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8115fdff)
Location: include/trace/events/sched.h:471
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
In kernel/sched/fair.c (ffffffff8115f1c2)
Location: include/trace/events/sched.h:471
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8117050f)
Location: include/trace/events/sched.h:471
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
In kernel/sched/fair.c (ffffffff8116d73c)
Location: include/trace/events/sched.h:471
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8117de57)
Location: include/trace/events/sched.h:471
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
In kernel/sched/fair.c (ffff800010146fa4)
Location: include/trace/events/sched.h:386
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
In kernel/sched/fair.c (c039526c)
Location: include/trace/events/sched.h:386
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
In kernel/sched/fair.c (c0000000001985e8)
Location: include/trace/events/sched.h:386
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
In kernel/sched/fair.c (ffffffe0000f282e)
Location: include/trace/events/sched.h:386
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
In kernel/sched/fair.c (ffffffff810e1235)
Location: include/trace/events/sched.h:386
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
In kernel/sched/fair.c (ffffffff810d0315)
Location: include/trace/events/sched.h:386
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
In kernel/sched/fair.c (ffffffff810dd5b5)
Location: include/trace/events/sched.h:386
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
In kernel/sched/fair.c (ffffffff810e9335)
Location: include/trace/events/sched.h:386
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
</ul>

## Differences
