# Function: <code>check_process_timers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f3b11)
Location: kernel/time/posix-cpu-timers.c:961
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810fac7b)
Location: kernel/time/posix-cpu-timers.c:934
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811085fb)
Location: kernel/time/posix-cpu-timers.c:930
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
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
In kernel/time/posix-cpu-timers.c (ffffffff8110a8c6)
Location: kernel/time/posix-cpu-timers.c:899
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81115a33)
Location: kernel/time/posix-cpu-timers.c:899
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81122219)
Location: kernel/time/posix-cpu-timers.c:910
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112d937)
Location: kernel/time/posix-cpu-timers.c:911
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81138327)
Location: kernel/time/posix-cpu-timers.c:910
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811442b3)
Location: kernel/time/posix-cpu-timers.c:903
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void check_process_timers(struct task_struct *tsk, struct list_head *firing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:896
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff811534a0-ffffffff81153676: check_process_timers (STB_LOCAL)
ffffffff81153fb6-ffffffff81154022: check_process_timers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void check_process_timers(struct task_struct *tsk, struct list_head *firing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:908
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:handle_posix_cpu_timers
```
**Symbols:**

```
ffffffff8114f760-ffffffff8114f936: check_process_timers (STB_LOCAL)
ffffffff81be3ae7-ffffffff81be3b53: check_process_timers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void check_process_timers(struct task_struct *tsk, struct list_head *firing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:908
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
**Symbols:**

```
ffffffff81150a80-ffffffff81150c59: check_process_timers (STB_LOCAL)
ffffffff81bd599a-ffffffff81bd5a06: check_process_timers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void check_process_timers(struct task_struct *tsk, struct list_head *firing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:966
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
**Symbols:**

```
ffffffff81174e50-ffffffff81175029: check_process_timers (STB_LOCAL)
ffffffff81cb1c6e-ffffffff81cb1cda: check_process_timers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void check_process_timers(struct task_struct *tsk, struct list_head *firing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:973
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
**Symbols:**

```
ffffffff811aa0d0-ffffffff811aa2d8: check_process_timers (STB_LOCAL)
ffffffff81e6321a-ffffffff81e63286: check_process_timers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void check_process_timers(struct task_struct *tsk, struct list_head *firing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811ea080)
Location: kernel/time/posix-cpu-timers.c:973
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
**Symbols:**

```
ffffffff811ea080-ffffffff811ea2e2: check_process_timers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void check_process_timers(struct task_struct *tsk, struct list_head *firing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fe790)
Location: kernel/time/posix-cpu-timers.c:974
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
**Symbols:**

```
ffffffff811fe790-ffffffff811fe9f2: check_process_timers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void check_process_timers(struct task_struct *tsk, struct list_head *firing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:974
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
**Symbols:**

```
ffffffff81214c70-ffffffff81214ef8: check_process_timers (STB_LOCAL)
ffffffff821b5cdc-ffffffff821b5cf1: check_process_timers.cold (STB_LOCAL)
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
In kernel/time/posix-cpu-timers.c (ffff8000101ae808)
Location: kernel/time/posix-cpu-timers.c:903
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
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
In kernel/time/posix-cpu-timers.c (c03f98f0)
Location: kernel/time/posix-cpu-timers.c:903
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
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
In kernel/time/posix-cpu-timers.c (c000000000212dd0)
Location: kernel/time/posix-cpu-timers.c:903
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
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
In kernel/time/posix-cpu-timers.c (ffffffe00013828a)
Location: kernel/time/posix-cpu-timers.c:903
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
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
In kernel/time/posix-cpu-timers.c (ffffffff8113ca63)
Location: kernel/time/posix-cpu-timers.c:903
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
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
In kernel/time/posix-cpu-timers.c (ffffffff8112f4e7)
Location: kernel/time/posix-cpu-timers.c:903
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
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
In kernel/time/posix-cpu-timers.c (ffffffff8113a783)
Location: kernel/time/posix-cpu-timers.c:903
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
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
In kernel/time/posix-cpu-timers.c (ffffffff81147243)
Location: kernel/time/posix-cpu-timers.c:903
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
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
