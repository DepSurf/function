# Function: <code>curr_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0340)
Location: kernel/sched/core.c:7661
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps
```
**Symbols:**

```
ffffffff810b0340-ffffffff810b0365: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2f70)
Location: kernel/sched/core.c:7690
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
```
**Symbols:**

```
ffffffff810b2f70-ffffffff810b2f95: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9560)
Location: kernel/sched/core.c:7843
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
```
**Symbols:**

```
ffffffff810b9560-ffffffff810b9585: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4140)
Location: kernel/sched/core.c:6056
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
```
**Symbols:**

```
ffffffff810b4140-ffffffff810b4165: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb3f0)
Location: kernel/sched/core.c:6124
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810bb3f0-ffffffff810bb415: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c28b0)
Location: kernel/sched/core.c:6244
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810c28b0-ffffffff810c28d5: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbbb0)
Location: kernel/sched/core.c:6225
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810cbbb0-ffffffff810cbbd5: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3c30)
Location: kernel/sched/core.c:6700
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810d3c30-ffffffff810d3c55: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de110)
Location: kernel/sched/core.c:6887
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810de110-ffffffff810de135: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e66c0)
Location: kernel/sched/core.c:7121
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810e66c0-ffffffff810e66e5: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e45c0)
Location: kernel/sched/core.c:8086
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810e45c0-ffffffff810e45e5: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e6570)
Location: kernel/sched/core.c:8455
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810e6570-ffffffff810e6595: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fdaa0)
Location: kernel/sched/core.c:9667
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810fdaa0-ffffffff810fdae5: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8111a4e0)
Location: kernel/sched/core.c:9990
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff8111a4e0-ffffffff8111a52d: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81141d60)
Location: kernel/sched/core.c:10170
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff81141d60-ffffffff81141dad: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114da30)
Location: kernel/sched/core.c:10314
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff8114da30-ffffffff8114da7d: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81159840)
Location: kernel/sched/core.c:10301
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff81159840-ffffffff8115988d: curr_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013db90)
Location: kernel/sched/core.c:6887
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffff80001013db90-ffff80001013dbd0: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038db68)
Location: kernel/sched/core.c:6887
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
c038db68-c038db9c: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018cb60)
Location: kernel/sched/core.c:6887
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
c00000000018cb60-c00000000018cb94: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8300)
Location: kernel/sched/core.c:6887
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810d8300-ffffffff810d8325: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6d10)
Location: kernel/sched/core.c:6887
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810c6d10-ffffffff810c6d35: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4af0)
Location: kernel/sched/core.c:6887
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810d4af0-ffffffff810d4b15: curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfee0)
Location: kernel/sched/core.c:6887
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
**Symbols:**

```
ffffffff810dfee0-ffffffff810dff05: curr_task (STB_GLOBAL)
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
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
