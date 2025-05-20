# Function: <code>pid_for_clock</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pid *pid_for_clock(const clockid_t clock, bool gettime);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81152b49)
Location: kernel/time/posix-cpu-timers.c:50
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
```
**Symbols:**

```
ffffffff81152710-ffffffff811527e4: pid_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pid *pid_for_clock(const clockid_t clock, bool gettime);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114edba)
Location: kernel/time/posix-cpu-timers.c:50
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
```
**Symbols:**

```
ffffffff8114e960-ffffffff8114ea34: pid_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pid *pid_for_clock(const clockid_t clock, bool gettime);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8115024a)
Location: kernel/time/posix-cpu-timers.c:50
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
```
**Symbols:**

```
ffffffff8114fe00-ffffffff8114fecd: pid_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pid *pid_for_clock(const clockid_t clock, bool gettime);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8117449a)
Location: kernel/time/posix-cpu-timers.c:50
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
```
**Symbols:**

```
ffffffff81174030-ffffffff811740fd: pid_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pid *pid_for_clock(const clockid_t clock, bool gettime);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811a92a2)
Location: kernel/time/posix-cpu-timers.c:57
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
```
**Symbols:**

```
ffffffff811a8d20-ffffffff811a8e14: pid_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pid *pid_for_clock(const clockid_t clock, bool gettime);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811e9112)
Location: kernel/time/posix-cpu-timers.c:57
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
```
**Symbols:**

```
ffffffff811e8b70-ffffffff811e8c64: pid_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pid *pid_for_clock(const clockid_t clock, bool gettime);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fd702)
Location: kernel/time/posix-cpu-timers.c:57
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
```
**Symbols:**

```
ffffffff811fd180-ffffffff811fd272: pid_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pid *pid_for_clock(const clockid_t clock, bool gettime);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81213902)
Location: kernel/time/posix-cpu-timers.c:57
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
```
**Symbols:**

```
ffffffff81213380-ffffffff81213472: pid_for_clock (STB_LOCAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
