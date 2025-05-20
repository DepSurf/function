# Function: <code>check_cpu_itimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, long long unsigned int *expires, long long unsigned int cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f2940)
Location: kernel/time/posix-cpu-timers.c:926
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff810f2940-ffffffff810f2a7b: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, long long unsigned int *expires, long long unsigned int cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f9a50)
Location: kernel/time/posix-cpu-timers.c:899
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff810f9a50-ffffffff810f9b84: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, long long unsigned int *expires, long long unsigned int cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811073e0)
Location: kernel/time/posix-cpu-timers.c:895
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff811073e0-ffffffff81107514: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, u64 *expires, u64 cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811097b0)
Location: kernel/time/posix-cpu-timers.c:872
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff811097b0-ffffffff811098b0: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, u64 *expires, u64 cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81114980)
Location: kernel/time/posix-cpu-timers.c:872
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff81114980-ffffffff81114a82: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81121120)
Location: kernel/time/posix-cpu-timers.c:883
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff81121120-ffffffff81121229: check_cpu_itimer.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112c840)
Location: kernel/time/posix-cpu-timers.c:884
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff8112c840-ffffffff8112c949: check_cpu_itimer.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81137210)
Location: kernel/time/posix-cpu-timers.c:883
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff81137210-ffffffff81137315: check_cpu_itimer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811433c0)
Location: kernel/time/posix-cpu-timers.c:876
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff811433c0-ffffffff811434bd: check_cpu_itimer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, u64 *expires, u64 cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811525b0)
Location: kernel/time/posix-cpu-timers.c:869
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
**Symbols:**

```
ffffffff811525b0-ffffffff8115269d: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, u64 *expires, u64 cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114e830)
Location: kernel/time/posix-cpu-timers.c:881
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
**Symbols:**

```
ffffffff8114e830-ffffffff8114e8eb: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, u64 *expires, u64 cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114fcd0)
Location: kernel/time/posix-cpu-timers.c:881
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
**Symbols:**

```
ffffffff8114fcd0-ffffffff8114fd8b: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, u64 *expires, u64 cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81173e50)
Location: kernel/time/posix-cpu-timers.c:939
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
**Symbols:**

```
ffffffff81173e50-ffffffff81173f08: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, u64 *expires, u64 cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811a8ac0)
Location: kernel/time/posix-cpu-timers.c:946
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
**Symbols:**

```
ffffffff811a8ac0-ffffffff811a8bd4: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, u64 *expires, u64 cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811e88e0)
Location: kernel/time/posix-cpu-timers.c:946
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
**Symbols:**

```
ffffffff811e88e0-ffffffff811e89f4: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, u64 *expires, u64 cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fcef0)
Location: kernel/time/posix-cpu-timers.c:947
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
**Symbols:**

```
ffffffff811fcef0-ffffffff811fd004: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, u64 *expires, u64 cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff812130e0)
Location: kernel/time/posix-cpu-timers.c:947
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
**Symbols:**

```
ffffffff812130e0-ffffffff812131f4: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ad540)
Location: kernel/time/posix-cpu-timers.c:876
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffff8000101ad540-ffff8000101ad66c: check_cpu_itimer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void check_cpu_itimer(struct task_struct *tsk, struct cpu_itimer *it, u64 *expires, u64 cur_time, int signo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f8468)
Location: kernel/time/posix-cpu-timers.c:876
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
c03f8468-c03f85a0: check_cpu_itimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c000000000211850)
Location: kernel/time/posix-cpu-timers.c:876
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
c000000000211850-c0000000002119c8: check_cpu_itimer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe0001374fe)
Location: kernel/time/posix-cpu-timers.c:876
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffe0001374fe-ffffffe0001375e2: check_cpu_itimer.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113bb70)
Location: kernel/time/posix-cpu-timers.c:876
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff8113bb70-ffffffff8113bc6d: check_cpu_itimer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112e530)
Location: kernel/time/posix-cpu-timers.c:876
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff8112e530-ffffffff8112e62d: check_cpu_itimer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81139890)
Location: kernel/time/posix-cpu-timers.c:876
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff81139890-ffffffff8113998d: check_cpu_itimer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81146360)
Location: kernel/time/posix-cpu-timers.c:876
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff81146360-ffffffff81146476: check_cpu_itimer.isra.0 (STB_LOCAL)
```
</details>
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
<code>long long unsigned int *expires</code> ➡️ <code>u64 *expires</code>
</li>
<li>
<b>Param type changed. </b>
<code>long long unsigned int cur_time</code> ➡️ <code>u64 cur_time</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
