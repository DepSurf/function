# Function: <code>cpu_timer_getexpires</code>

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
In kernel/time/posix-cpu-timers.c (ffffffff81142dc8)
Location: include/linux/posix-timers.h:92
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:arm_timer
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
In kernel/time/posix-cpu-timers.c (ffffffff8115376c)
Location: include/linux/posix-timers.h:92
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:arm_timer
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
In kernel/time/posix-cpu-timers.c (ffffffff8114fba8)
Location: include/linux/posix-timers.h:93
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:arm_timer
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
In kernel/time/posix-cpu-timers.c (ffffffff81150fe9)
Location: include/linux/posix-timers.h:93
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:arm_timer
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
In kernel/time/posix-cpu-timers.c (ffffffff811753b9)
Location: include/linux/posix-timers.h:100
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:arm_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
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
In kernel/time/posix-cpu-timers.c (ffffffff811a9d06)
Location: include/linux/posix-timers.h:99
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:arm_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
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
In kernel/time/posix-cpu-timers.c (ffffffff811e9c66)
Location: include/linux/posix-timers.h:99
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:arm_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
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
In kernel/time/posix-cpu-timers.c (ffffffff811fe356)
Location: include/linux/posix-timers.h:102
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:arm_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
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
In kernel/time/posix-cpu-timers.c (ffffffff812146e6)
Location: include/linux/posix-timers.h:78
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:arm_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
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
In kernel/time/posix-cpu-timers.c (ffff8000101ad0e0)
Location: include/linux/posix-timers.h:92
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:arm_timer
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
In kernel/time/posix-cpu-timers.c (c03f9114)
Location: include/linux/posix-timers.h:92
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:arm_timer
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
In kernel/time/posix-cpu-timers.c (c000000000210ec8)
Location: include/linux/posix-timers.h:92
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:arm_timer
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
In kernel/time/posix-cpu-timers.c (ffffffe000137d96)
Location: include/linux/posix-timers.h:92
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:arm_timer
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
In kernel/time/posix-cpu-timers.c (ffffffff8113b578)
Location: include/linux/posix-timers.h:92
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:arm_timer
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
In kernel/time/posix-cpu-timers.c (ffffffff8112dfb8)
Location: include/linux/posix-timers.h:92
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:arm_timer
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
In kernel/time/posix-cpu-timers.c (ffffffff81139298)
Location: include/linux/posix-timers.h:92
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:arm_timer
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
In kernel/time/posix-cpu-timers.c (ffffffff81145d38)
Location: include/linux/posix-timers.h:92
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:arm_timer
```
</details>
</li>
</ul>

## Differences
