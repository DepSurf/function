# Function: <code>thread_group_cputimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void thread_group_cputimer(struct task_struct *tsk, struct task_cputime *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f2bc0)
Location: kernel/time/posix-cpu-timers.c:230
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/posix-cpu-timers.c:cpu_timer_sample_group
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff810f2bc0-ffffffff810f2cb6: thread_group_cputimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void thread_group_cputimer(struct task_struct *tsk, struct task_cputime *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f9cd0)
Location: kernel/time/posix-cpu-timers.c:230
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_timer_sample_group
```
**Symbols:**

```
ffffffff810f9cd0-ffffffff810f9dc6: thread_group_cputimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void thread_group_cputimer(struct task_struct *tsk, struct task_cputime *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81107660)
Location: kernel/time/posix-cpu-timers.c:229
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_timer_sample_group
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff81107660-ffffffff81107756: thread_group_cputimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void thread_group_cputimer(struct task_struct *tsk, struct task_cputime *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811099f0)
Location: kernel/time/posix-cpu-timers.c:210
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_timer_sample_group
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff811099f0-ffffffff81109ae6: thread_group_cputimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void thread_group_cputimer(struct task_struct *tsk, struct task_cputime *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81114bd0)
Location: kernel/time/posix-cpu-timers.c:211
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_timer_sample_group
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff81114bd0-ffffffff81114cc6: thread_group_cputimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void thread_group_cputimer(struct task_struct *tsk, struct task_cputime *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81121370)
Location: kernel/time/posix-cpu-timers.c:212
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_timer_sample_group
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff81121370-ffffffff81121466: thread_group_cputimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void thread_group_cputimer(struct task_struct *tsk, struct task_cputime *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112ca90)
Location: kernel/time/posix-cpu-timers.c:212
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_timer_sample_group
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff8112ca90-ffffffff8112cb86: thread_group_cputimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void thread_group_cputimer(struct task_struct *tsk, struct task_cputime *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81137460)
Location: kernel/time/posix-cpu-timers.c:212
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_timer_sample_group
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff81137460-ffffffff81137556: thread_group_cputimer (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
