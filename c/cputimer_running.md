# Function: <code>cputimer_running</code>

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
In kernel/sched/cputime.c (ffffffff810b1705)
Location: kernel/sched/stats.h:172
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_user_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/fair.c (ffffffff810b4b2a)
Location: kernel/sched/stats.h:172
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810bfaef)
Location: kernel/sched/stats.h:172
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c2201)
Location: kernel/sched/stats.h:172
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810c315e)
Location: kernel/sched/stats.h:172
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/cputime.c (ffffffff810b424b)
Location: kernel/sched/stats.h:177
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810b769a)
Location: kernel/sched/stats.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810c341e)
Location: kernel/sched/stats.h:177
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c5bd9)
Location: kernel/sched/stats.h:177
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810c6ada)
Location: kernel/sched/stats.h:177
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/cputime.c (ffffffff810ba873)
Location: kernel/sched/stats.h:179
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810bf9aa)
Location: kernel/sched/stats.h:179
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810c948e)
Location: kernel/sched/stats.h:179
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cbb99)
Location: kernel/sched/stats.h:179
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810ccaba)
Location: kernel/sched/stats.h:179
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
</details>
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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
