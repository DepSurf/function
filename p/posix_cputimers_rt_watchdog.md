# Function: <code>posix_cputimers_rt_watchdog</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ef647)
Location: include/linux/posix-timers.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (ffffffff810f8f2d)
Location: include/linux/posix-timers.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (ffffffff810f711d)
Location: include/linux/posix-timers.h:149
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (ffffffff810f926d)
Location: include/linux/posix-timers.h:149
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (ffffffff8111483f)
Location: include/linux/posix-timers.h:156
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/build_policy.c (ffffffff81138020)
Location: include/linux/posix-timers.h:155
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
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
In kernel/sched/build_policy.c (ffffffff811626e0)
Location: include/linux/posix-timers.h:155
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
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
In kernel/sched/build_policy.c (ffffffff81172e60)
Location: include/linux/posix-timers.h:160
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
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
In kernel/sched/build_policy.c (ffffffff81180774)
Location: include/linux/posix-timers.h:98
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
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
In kernel/sched/rt.c (ffff8000101508b8)
Location: include/linux/posix-timers.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (c039e57c)
Location: include/linux/posix-timers.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (c0000000001a49c0)
Location: include/linux/posix-timers.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (ffffffe0000f8f62)
Location: include/linux/posix-timers.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (ffffffff810e8ea7)
Location: include/linux/posix-timers.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (ffffffff810d8a07)
Location: include/linux/posix-timers.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (ffffffff810e5b77)
Location: include/linux/posix-timers.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (ffffffff810f0a3b)
Location: include/linux/posix-timers.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
</details>
</li>
</ul>

## Differences
