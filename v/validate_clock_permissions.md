# Function: <code>validate_clock_permissions</code>

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
In kernel/time/posix-cpu-timers.c (ffffffff81143305)
Location: kernel/time/posix-cpu-timers.c:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
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
In kernel/time/posix-cpu-timers.c (ffffffff81152b45)
Location: kernel/time/posix-cpu-timers.c:90
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
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
In kernel/time/posix-cpu-timers.c (ffffffff8114edb5)
Location: kernel/time/posix-cpu-timers.c:90
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
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
In kernel/time/posix-cpu-timers.c (ffffffff81150245)
Location: kernel/time/posix-cpu-timers.c:90
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
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
In kernel/time/posix-cpu-timers.c (ffffffff81174495)
Location: kernel/time/posix-cpu-timers.c:90
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
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
In kernel/time/posix-cpu-timers.c (ffffffff811a929d)
Location: kernel/time/posix-cpu-timers.c:97
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
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
In kernel/time/posix-cpu-timers.c (ffffffff811e910d)
Location: kernel/time/posix-cpu-timers.c:97
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
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
In kernel/time/posix-cpu-timers.c (ffffffff811fd6fd)
Location: kernel/time/posix-cpu-timers.c:97
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
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
In kernel/time/posix-cpu-timers.c (ffffffff812138fd)
Location: kernel/time/posix-cpu-timers.c:97
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
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
In kernel/time/posix-cpu-timers.c (ffff8000101ad438)
Location: kernel/time/posix-cpu-timers.c:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
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
In kernel/time/posix-cpu-timers.c (c03f83a4)
Location: kernel/time/posix-cpu-timers.c:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
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
In kernel/time/posix-cpu-timers.c (c00000000021172c)
Location: kernel/time/posix-cpu-timers.c:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
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
In kernel/time/posix-cpu-timers.c (ffffffe00013741e)
Location: kernel/time/posix-cpu-timers.c:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
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
In kernel/time/posix-cpu-timers.c (ffffffff8113bab5)
Location: kernel/time/posix-cpu-timers.c:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
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
In kernel/time/posix-cpu-timers.c (ffffffff8112e475)
Location: kernel/time/posix-cpu-timers.c:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
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
In kernel/time/posix-cpu-timers.c (ffffffff811397d5)
Location: kernel/time/posix-cpu-timers.c:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
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
In kernel/time/posix-cpu-timers.c (ffffffff811462a5)
Location: kernel/time/posix-cpu-timers.c:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
```
</details>
</li>
</ul>

## Differences
