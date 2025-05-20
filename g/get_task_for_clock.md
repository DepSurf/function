# Function: <code>get_task_for_clock</code>

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
In kernel/time/posix-cpu-timers.c (ffffffff811432cb)
Location: kernel/time/posix-cpu-timers.c:106
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ad3dc)
Location: kernel/time/posix-cpu-timers.c:106
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
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
In kernel/time/posix-cpu-timers.c (c03f8360)
Location: kernel/time/posix-cpu-timers.c:106
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
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
In kernel/time/posix-cpu-timers.c (c0000000002116c8)
Location: kernel/time/posix-cpu-timers.c:106
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
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
In kernel/time/posix-cpu-timers.c (ffffffe0001373d6)
Location: kernel/time/posix-cpu-timers.c:106
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
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
In kernel/time/posix-cpu-timers.c (ffffffff8113ba7b)
Location: kernel/time/posix-cpu-timers.c:106
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
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
In kernel/time/posix-cpu-timers.c (ffffffff8112e43b)
Location: kernel/time/posix-cpu-timers.c:106
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
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
In kernel/time/posix-cpu-timers.c (ffffffff8113979b)
Location: kernel/time/posix-cpu-timers.c:106
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
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
In kernel/time/posix-cpu-timers.c (ffffffff8114626b)
Location: kernel/time/posix-cpu-timers.c:106
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
</details>
</li>
</ul>

## Differences
