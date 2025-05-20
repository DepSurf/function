# Function: <code>cpufreq_update_this_cpu</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c24d3)
Location: kernel/sched/sched.h:1810
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c9463)
Location: kernel/sched/sched.h:1810
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cbb73)
Location: kernel/sched/sched.h:1810
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/fair.c (ffffffff810bd120)
Location: kernel/sched/sched.h:2078
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c46f4)
Location: kernel/sched/sched.h:2078
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c7e30)
Location: kernel/sched/sched.h:2078
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
</details>
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
