# Function: <code>cpu_timer_sample_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct *p, long long unsigned int *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f2cc0)
Location: kernel/time/posix-cpu-timers.c:562
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
```
**Symbols:**

```
ffffffff810f2cc0-ffffffff810f2d4b: cpu_timer_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct *p, long long unsigned int *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f9dd0)
Location: kernel/time/posix-cpu-timers.c:565
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff810f9dd0-ffffffff810f9e5b: cpu_timer_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct *p, long long unsigned int *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81107760)
Location: kernel/time/posix-cpu-timers.c:561
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81107760-ffffffff811077eb: cpu_timer_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct *p, u64 *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81109af0)
Location: kernel/time/posix-cpu-timers.c:544
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81109af0-ffffffff81109b7b: cpu_timer_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct *p, u64 *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81114cd0)
Location: kernel/time/posix-cpu-timers.c:545
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81114cd0-ffffffff81114d5b: cpu_timer_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct *p, u64 *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81121470)
Location: kernel/time/posix-cpu-timers.c:546
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81121470-ffffffff811214fb: cpu_timer_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct *p, u64 *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112cb90)
Location: kernel/time/posix-cpu-timers.c:546
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff8112cb90-ffffffff8112cc1b: cpu_timer_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct *p, u64 *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81137560)
Location: kernel/time/posix-cpu-timers.c:546
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81137560-ffffffff811375eb: cpu_timer_sample_group (STB_LOCAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long long unsigned int *sample</code> ➡️ <code>u64 *sample</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
