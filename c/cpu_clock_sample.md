# Function: <code>cpu_clock_sample</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpu_clock_sample(const clockid_t which_clock, struct task_struct *p, long long unsigned int *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f2470)
Location: kernel/time/posix-cpu-timers.c:180
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff810f2470-ffffffff810f24c5: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpu_clock_sample(const clockid_t which_clock, struct task_struct *p, long long unsigned int *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f9550)
Location: kernel/time/posix-cpu-timers.c:180
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
```
**Symbols:**

```
ffffffff810f9550-ffffffff810f95a5: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpu_clock_sample(const clockid_t which_clock, struct task_struct *p, long long unsigned int *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81106ee0)
Location: kernel/time/posix-cpu-timers.c:179
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
```
**Symbols:**

```
ffffffff81106ee0-ffffffff81106f35: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpu_clock_sample(const clockid_t which_clock, struct task_struct *p, u64 *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81109370)
Location: kernel/time/posix-cpu-timers.c:160
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
```
**Symbols:**

```
ffffffff81109370-ffffffff811093c5: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpu_clock_sample(const clockid_t which_clock, struct task_struct *p, u64 *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81114540)
Location: kernel/time/posix-cpu-timers.c:161
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
```
**Symbols:**

```
ffffffff81114540-ffffffff81114595: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpu_clock_sample(const clockid_t which_clock, struct task_struct *p, u64 *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81120cf0)
Location: kernel/time/posix-cpu-timers.c:162
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
```
**Symbols:**

```
ffffffff81120cf0-ffffffff81120d45: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpu_clock_sample(const clockid_t which_clock, struct task_struct *p, u64 *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112c410)
Location: kernel/time/posix-cpu-timers.c:162
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
```
**Symbols:**

```
ffffffff8112c410-ffffffff8112c465: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpu_clock_sample(const clockid_t which_clock, struct task_struct *p, u64 *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81136dc0)
Location: kernel/time/posix-cpu-timers.c:162
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
```
**Symbols:**

```
ffffffff81136dc0-ffffffff81136e1b: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81143500)
Location: kernel/time/posix-cpu-timers.c:197
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff81143500-ffffffff81143536: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811527f0)
Location: kernel/time/posix-cpu-timers.c:187
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff811527f0-ffffffff81152826: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114ea40)
Location: kernel/time/posix-cpu-timers.c:187
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff8114ea40-ffffffff8114ea76: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114fed0)
Location: kernel/time/posix-cpu-timers.c:187
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff8114fed0-ffffffff8114ff06: cpu_clock_sample (STB_LOCAL)
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
In kernel/time/posix-cpu-timers.c (ffffffff811747f3)
Location: kernel/time/posix-cpu-timers.c:187
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
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
In kernel/time/posix-cpu-timers.c (ffffffff811a961e)
Location: kernel/time/posix-cpu-timers.c:194
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
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
In kernel/time/posix-cpu-timers.c (ffffffff811e954e)
Location: kernel/time/posix-cpu-timers.c:194
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
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
In kernel/time/posix-cpu-timers.c (ffffffff811fdc3e)
Location: kernel/time/posix-cpu-timers.c:194
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff812132e0)
Location: kernel/time/posix-cpu-timers.c:194
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff812132e0-ffffffff8121336c: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ad710)
Location: kernel/time/posix-cpu-timers.c:197
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffff8000101ad710-ffff8000101ad780: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f865c)
Location: kernel/time/posix-cpu-timers.c:197
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
c03f865c-c03f86f8: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c000000000211a90)
Location: kernel/time/posix-cpu-timers.c:197
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
c000000000211a90-c000000000211b08: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe00013766e)
Location: kernel/time/posix-cpu-timers.c:197
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffe00013766e-ffffffe0001376d2: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113bcb0)
Location: kernel/time/posix-cpu-timers.c:197
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff8113bcb0-ffffffff8113bce6: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112e670)
Location: kernel/time/posix-cpu-timers.c:197
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff8112e670-ffffffff8112e6e3: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811399d0)
Location: kernel/time/posix-cpu-timers.c:197
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff811399d0-ffffffff81139a06: cpu_clock_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811464c0)
Location: kernel/time/posix-cpu-timers.c:197
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff811464c0-ffffffff811464f6: cpu_clock_sample (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const clockid_t clkid</code>
</li>
<li>
<b>Param removed. </b>
<code>const clockid_t which_clock</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 *sample</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
