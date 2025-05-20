# Function: <code>rt_queue_push_tasks</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d4094)
Location: kernel/sched/rt.c:358
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff810ddd2d)
Location: kernel/sched/rt.c:360
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff810e4d3a)
Location: kernel/sched/rt.c:360
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff810ee212)
Location: kernel/sched/rt.c:361
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff810f7bd2)
Location: kernel/sched/rt.c:363
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff810f5dd5)
Location: kernel/sched/rt.c:363
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff810f8135)
Location: kernel/sched/rt.c:363
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff811137a1)
Location: kernel/sched/rt.c:374
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/build_policy.c (ffffffff811384ee)
Location: kernel/sched/rt.c:419
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/build_policy.c (ffffffff81162b98)
Location: kernel/sched/rt.c:419
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/build_policy.c (ffffffff81173318)
Location: kernel/sched/rt.c:419
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/build_policy.c (ffffffff81180bf7)
Location: kernel/sched/rt.c:375
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffff80001014eec0)
Location: kernel/sched/rt.c:361
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (c039d33c)
Location: kernel/sched/rt.c:361
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (c0000000001a32e8)
Location: kernel/sched/rt.c:361
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffe0000f7d96)
Location: kernel/sched/rt.c:361
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff810e7f0b)
Location: kernel/sched/rt.c:361
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff810d7562)
Location: kernel/sched/rt.c:361
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff810e4742)
Location: kernel/sched/rt.c:361
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff810f0bcb)
Location: kernel/sched/rt.c:361
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
</details>
</li>
</ul>

## Differences
