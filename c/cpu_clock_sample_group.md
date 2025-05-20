# Function: <code>cpu_clock_sample_group</code>

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
In kernel/time/posix-cpu-timers.c (ffffffff810f25dd)
Location: kernel/time/posix-cpu-timers.c:262
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
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
In kernel/time/posix-cpu-timers.c (ffffffff810f96c3)
Location: kernel/time/posix-cpu-timers.c:262
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
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
In kernel/time/posix-cpu-timers.c (ffffffff81107053)
Location: kernel/time/posix-cpu-timers.c:261
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
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
In kernel/time/posix-cpu-timers.c (ffffffff81109461)
Location: kernel/time/posix-cpu-timers.c:242
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
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
In kernel/time/posix-cpu-timers.c (ffffffff81114631)
Location: kernel/time/posix-cpu-timers.c:243
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
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
In kernel/time/posix-cpu-timers.c (ffffffff81120dde)
Location: kernel/time/posix-cpu-timers.c:244
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
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
In kernel/time/posix-cpu-timers.c (ffffffff8112c4fe)
Location: kernel/time/posix-cpu-timers.c:244
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
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
In kernel/time/posix-cpu-timers.c (ffffffff81136ea2)
Location: kernel/time/posix-cpu-timers.c:244
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81142e70)
Location: kernel/time/posix-cpu-timers.c:343
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff81142e70-ffffffff81142fa5: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81152bc0)
Location: kernel/time/posix-cpu-timers.c:331
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
**Symbols:**

```
ffffffff81152bc0-ffffffff81152cf5: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114ee50)
Location: kernel/time/posix-cpu-timers.c:331
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
**Symbols:**

```
ffffffff8114ee50-ffffffff8114ef85: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811502e0)
Location: kernel/time/posix-cpu-timers.c:331
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
**Symbols:**

```
ffffffff811502e0-ffffffff81150415: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81174530)
Location: kernel/time/posix-cpu-timers.c:333
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
**Symbols:**

```
ffffffff81174530-ffffffff81174683: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811a92f0)
Location: kernel/time/posix-cpu-timers.c:340
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
**Symbols:**

```
ffffffff811a92f0-ffffffff811a949b: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811e91e0)
Location: kernel/time/posix-cpu-timers.c:340
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
**Symbols:**

```
ffffffff811e91e0-ffffffff811e938b: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fd8e0)
Location: kernel/time/posix-cpu-timers.c:339
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
**Symbols:**

```
ffffffff811fd8e0-ffffffff811fda72: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81213c00)
Location: kernel/time/posix-cpu-timers.c:339
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
**Symbols:**

```
ffffffff81213c00-ffffffff81213d92: cpu_clock_sample_group (STB_LOCAL)
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
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ad780)
Location: kernel/time/posix-cpu-timers.c:343
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffff8000101ad780-ffff8000101ad918: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f86f8)
Location: kernel/time/posix-cpu-timers.c:343
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
c03f86f8-c03f8918: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c000000000210fa0)
Location: kernel/time/posix-cpu-timers.c:343
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
c000000000210fa0-c0000000002111d0: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe000136ff6)
Location: kernel/time/posix-cpu-timers.c:343
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffe000136ff6-ffffffe000137118: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113b620)
Location: kernel/time/posix-cpu-timers.c:343
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff8113b620-ffffffff8113b755: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112e060)
Location: kernel/time/posix-cpu-timers.c:343
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff8112e060-ffffffff8112e195: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81139340)
Location: kernel/time/posix-cpu-timers.c:343
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff81139340-ffffffff81139475: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 cpu_clock_sample_group(const clockid_t clkid, struct task_struct *p, bool start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81145de0)
Location: kernel/time/posix-cpu-timers.c:343
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
**Symbols:**

```
ffffffff81145de0-ffffffff81145f15: cpu_clock_sample_group (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
