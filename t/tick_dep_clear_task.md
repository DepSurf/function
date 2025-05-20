# Function: <code>tick_dep_clear_task</code>

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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:253
Inline: True
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:251
Inline: True
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:252
Inline: True
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:245
Inline: True
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:266
Inline: True
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:266
Inline: True
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:277
Inline: True
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:277
Inline: True
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
In kernel/rcu/tree.c (0)
Location: include/linux/tick.h:285
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:285
Inline: True
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
In kernel/rcu/tree.c (0)
Location: include/linux/tick.h:285
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:285
Inline: True
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
In kernel/rcu/tree.c (0)
Location: include/linux/tick.h:286
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:286
Inline: True
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
In kernel/rcu/tree.c (0)
Location: include/linux/tick.h:290
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:290
Inline: True
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
In kernel/rcu/tree.c (0)
Location: include/linux/tick.h:290
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:290
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
In kernel/rcu/tree.c (0)
Location: include/linux/tick.h:290
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:290
Inline: True
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
In kernel/rcu/tree.c (0)
Location: include/linux/tick.h:292
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:292
Inline: True
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
In kernel/rcu/tree.c (ffffffff811de193)
Location: include/linux/tick.h:245
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81214bf3)
Location: include/linux/tick.h:245
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_thread_timers
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:277
Inline: True
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:277
Inline: True
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:277
Inline: True
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:277
Inline: True
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:277
Inline: True
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
In kernel/time/posix-cpu-timers.c (ffffffff8112f772)
Location: include/linux/tick.h:244
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:277
Inline: True
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
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/tick.h:277
Inline: True
```
</details>
</li>
</ul>

## Differences
