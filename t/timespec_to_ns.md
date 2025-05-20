# Function: <code>timespec_to_ns</code>

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
In kernel/time/itimer.c (ffffffff810f0228)
Location: include/linux/time.h:217
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/time.h:217
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
In kernel/time/itimer.c (ffffffff810f7258)
Location: include/linux/time.h:230
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810fa823)
Location: include/linux/time.h:230
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
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
In kernel/time/posix-cpu-timers.c (ffffffff811081a3)
Location: include/linux/time.h:228
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/time/itimer.c (ffffffff81109918)
Location: include/linux/time.h:228
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
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
In kernel/time/posix-cpu-timers.c (ffffffff81109fd1)
Location: include/linux/time.h:231
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
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
